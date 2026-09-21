<!-- BEGIN:brand-rules -->
# Read `brand/DESIGN.md` before any UI work

This project has a brand kit at `brand/`. `brand/DESIGN.md` is the whole spec — color, type,
layout, shapes, components, voice — with machine-readable tokens in its front matter.

1. **Read `brand/DESIGN.md` first.** It wins over taste. Its front matter is generated from
   `brand/tokens/tokens.json`; if prose and tokens disagree, the tokens are right.
2. **Every color, font, size, radius and duration in UI code references a `--mv-*` token.** No new
   hex, no new font family, no new radius. If you need a value that does not exist, add it to
   `tokens.json` and rebuild — never inline it.
3. **Import order:** `brand/tokens/tokens.css` first (it carries the font `@import` and the
   `:root` variables), then `brand/css/mia-for-vp.css`. Tailwind instead:
   `presets: [require('./brand/tokens/tailwind.preset.js')]`.
4. **Rebuild and prove it before calling UI work done:**
   ```bash
   python3 ~/.claude/skills/brand-kit/scripts/build_tokens.py brand/ --check --design DESIGN.md
   python3 ~/.claude/skills/brand-kit/scripts/lint_kit.py --tokens brand/tokens/tokens.json brand/css brand/preview <your source dir>
   python3 ~/.claude/skills/brand-kit/scripts/contrast.py brand/
   ```
   `brand/DESIGN.md` is deliberately not linted: its front matter lists the retired colors.
5. **`brand/preview/index.html` is the visual test.** If a change makes the preview wrong, the
   change is wrong.
6. **Never invent campaign facts.** Election date, platform points, quotes, numbers and Mia's
   surname ship as visible `[placeholders]` until someone supplies the real thing.
<!-- END:brand-rules -->

<!-- BEGIN:project-tracker-rules -->
# Keep `PROJECT_TRACKER.md` current — every agent, every session

This repo uses **one persistent status file** as the shared source of truth, built by multiple AI
agents. The real file lives in the memory vault at
`/Users/graydonwebster/Desktop/Context/projects/mia-vp-campaign/PROJECT_TRACKER.md`; the repo root holds a
`PROJECT_TRACKER.md` symlink pointing at it, so reading or editing the repo-root path works normally. It must always be readable by the human owner: at a
glance it says what's been built, what's being worked on, and what still needs to be implemented
and tested. Whoever you are (Claude Code, Codex, Cursor, etc.):

1. **Read it first** to orient before substantive work — the status board (§2), traps (§7) and
   standing rules (§8) before you touch anything. §6 records what is already verified; trust it
   instead of re-proving it. Check §5 (repo state) so you don't collide or assume something is on
   `main` when it's still in a worktree.
2. **Do not relitigate §8.** Those decisions are settled. If one is genuinely wrong, say so and get
   a human ruling; do not quietly work around it.
3. **Update it as you build** — move rows on the §2 status board (built / in progress / to build,
   tested / untested), record verification with **numbers** in §6, add a dated pass note (§10) and
   a changelog row (§11, with the commit hash once committed), refresh §5, record any new locked
   decision in §8, and bump **Last updated**.
4. **Anything that cost you a debugging cycle goes in §7 immediately**, while you still remember
   the real cause. Symptom, cause, standing instruction.
5. **Evidence, not adjectives.** "Tested and works" is worthless to the next agent and will be
   trusted anyway. Write what you ran and what it returned.
6. **Never rewrite history.** Supersede with a struck, dated note.
7. Don't duplicate the deep specs — link to them.
8. **If the repo root has no tracker, create it in the vault and symlink it; never create a second copy.**

**Transient companions.** `HANDOFF.md` (written by a handoff at a stopping point) and `goal.md`
(one long-running goal run) may exist beside the tracker. They never outlive their use: read a
handoff, fold anything durable into the tracker, delete it; when a goal run completes, graduate
its outcomes into the tracker and delete it.

**Long-running / autonomous runs (`/loop`, `/goal`, multi-step tasks):** re-read
`PROJECT_TRACKER.md` periodically to re-orient — refresh on the plan, see where the project is,
and decide what to do next, especially if you've drifted or lost context.

Treat this as part of "done": a change isn't finished until the tracker reflects it.
<!-- END:project-tracker-rules -->

