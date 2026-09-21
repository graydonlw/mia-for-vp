# Mia for VP — brand brief

The interview behind `DESIGN.md`. Answers from Graydon on 2026-09-20 (Mia is his sister; she has not
been in the room yet, so anything marked below as hers to confirm really is hers to confirm).

## Assumed, confirm

1. **Stack** — plain HTML + CSS, deployed as a static site to Vercel. Graydon said "I'll host it on
   Vercel later" without naming a framework; all four token formats are generated either way, so
   switching to Next + Tailwind costs nothing but a different import line.
2. **Mia's last name** is not recorded anywhere in the kit. The wordmark is "Mia for VP"; if the
   ballot needs a surname, the `h4` wordmark takes it without any other change.
3. **Election date, voting method, grade, platform points, and her "why I'm running" line** are all
   placeholders. Nothing in the kit invents them.
4. **Handwriting accent face** (Caveat) was prototyped in the chosen direction and left out of the
   token set. One decision away from being added; see Typography.
5. **The slogan and the page structure are open**, at Graydon's request on 2026-09-20 — alternative
   directions still to be proposed. The visual system does not depend on which one wins.
6. **Personality word "Playful"** was offered and not selected; it survives in the shapes rather than
   in the writing.

## Answers

| Question | Answer |
|---|---|
| Positioning | A campaign site that makes a CCA student decide in under a minute that Mia is worth voting for |
| Personality | Warm · Optimistic · Confident |
| Register | Light-first; one dark field (the footer) and no dark hero |
| Existing material | A slogan ("I won't go M.I.A."), photos of Mia to come, school colors to consider. No logo, no site, no Figma |
| The one idea | Soft, round, and impossible to miss — every shape is a circle, a pill, or a 24px corner; softness comes from shape and type, not from washing the color out |
| Signature detail | The petal pill (`.mv-mark`) behind one word per headline |
| Accent count | One. `rose` carries every interactive job; `petal`/`blush` are fields; status colors are roles, not brand accents |
| Corners | Fully round buttons and badges, 24px cards, 16px inputs, the arch for photos |
| Depth | Flat, borders only. One 1px shadow, under the mobile Vote bar |
| Type | Inter headlines + Nunito body + IBM Plex Mono labels |
| Weight policy | Inter 700 at display/h1/h2 and 600 at h3–h5; Nunito 400 body, 700 for buttons, badges, labels, nav |
| Case | Sentence case everywhere; uppercase only in `badge`, `overline` and `credit` |
| Fonts load from | Google Fonts, one request, `display=swap` |
| First screen needs | Nav, hero, platform cards, about block with photo |
| Kit lives in | `brand/` at the repo root |
| Icons | Lucide, 24 grid, 2px stroke, round caps |
| School colors | Checked (read live from ccobacademy.com; both hexes are in the retired list) and deliberately excluded — the blue fights the pinks and implies a school endorsement nobody has given |

## Directions that were considered and dropped

| Direction | Why not |
|---|---|
| A — Soft Glow (blush→lilac gradient blooms, plum buttons) | Liked less than B; the gradients fought the flat-shape idea |
| C — Blush & School Blue (CCA blue as ink and buttons) | Reads school-official rather than personal |
| B — Petal Poster, original (square corners, Bricolage Grotesque) | Chosen for palette, rejected for shape and type: "softer, rounder, playful" |
| Serif headline study (Fraunces, Instrument Serif, DM Serif Display, Quicksand) | "Further from what I want" — serifs dropped entirely |
| Rounded study (Fredoka, Quicksand, Baloo 2, Comfortaa) | ~~**Fredoka chosen**~~ — superseded 2026-09-20: the mock Graydon approved had rendered in its Helvetica fallback, so the rounded face was never what he picked. Display face is now **Inter**; the rounded *shape* treatment (24px corners, round buttons, petal pill) stays |
| Mauve-plum palette (the first version of B-Round) | "A little more pink and a little less plum" — the whole ramp was shifted toward true pink on 2026-09-20 |

## What changed after the first pink pass

Shifting the palette pinker broke contrast in two places, and both were fixed in the values rather
than waived: the first pink missed AA with white text at 4.35:1 (the rose is now 4.67:1),
and the same pink as a body-size link missed on every field (links are now one step deeper, 7.05:1 on the
page field). Every other retired hex is listed in `DESIGN.md`'s front matter.
