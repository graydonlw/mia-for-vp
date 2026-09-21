# Still needed from Mia

Live at **https://mia-for-vp.vercel.app** — every push to `main` redeploys it.

Everything below is placeholder copy sitting in `index.html`, marked
`[in brackets]` on the page, per `AGENTS.md` rule 6 and `brand/DESIGN.md`
Don't #9: no invented promises, quotes, numbers or dates. Tick these off as
they come in.

## Blocking a real launch

These three are the difference between a draft and something you can put a QR
code on.

- [ ] **Election date.** Set `ELECTION_DATE` in the config block at the bottom of
      `index.html` (format `"2026-10-08"`). It fills the date into the hero
      countdown, the How to vote cards, the CTA, the footer, and the page title.
      One edit, five places.
- [ ] **The three promises.** Specific and checkable, in her words. "A vending
      machine in the north hall by November" beats "more school spirit." Goes in
      `#platform`.
- [x] ~~**A photo.**~~ Done 2026-09-21 — three supplied and wired in: the hero
      arch, the About arch, and the round portrait in the vote CTA. `og:image`
      is set, so link previews are no longer blank.

## Needed, but the page survives without them

- [ ] **Voting logistics** — the room or period, which grades vote, whether
      students need anything with them. Goes in the three `#vote` cards.

## Optional

- [ ] **Campaign Instagram.** If she has one, set `INSTAGRAM` in the config
      block and the links turn on by themselves. If not, leave it `null` and
      they stay hidden.
- [ ] **Confirm the office is Vice President.** The whole site says VP because
      the brand kit did. Nobody has actually confirmed it.

## Before it goes public

- [ ] Delete `<div id="draft-banner">` at the top of `index.html`.
- [ ] Delete every element with `class="todo"`. Those are the grey notes-to-self
      under each section.
- [ ] Search the file for `[` and make sure no bracketed placeholder survived.
- [ ] Scan the QR code on a real phone before printing any of them. The codes
      live in `brand/assets/qr/` and the printable sheet is
      `brand/preview/qr.html` — open it and print to PDF. It decodes in software
      down to 150px, but a real camera is the only test that counts.
- [ ] **Re-generate the QR codes if the URL ever changes.** They are pointed at
      `https://mia-for-vp.vercel.app`. A custom domain, or anything else that
      moves the site, makes every printed code dead paper.
- [ ] Record the pass in `PROJECT_TRACKER.md` (§2, §6, §10, §11). The tracker is
      a symlink into the local vault and is gitignored, so it cannot be updated
      from the project thread — it has to happen on the machine that has it.

## Decisions already made, so nobody relitigates them

- Slogan is **"Lead with Grace"**. "I won't go M.I.A." is kept as one line at the
  end of the About section. Cut it if Mia doesn't like it.
- The page is **four sections** — hero, platform, about, how to vote (2026-09-20).
  "The job", her letter, the quotes block and the feedback section were cut as
  extra pages; the MVP in `PROJECT_TRACKER.md` §3 is hero + three platform cards
  + about with photo + vote CTA. If feedback comes back, it goes through a
  **Google Form**, not an on-page form: a public repo makes any form endpoint key
  scrapeable.
- No phone numbers or personal email addresses on the page, and no other
  students' names or faces without a parent's okay.
