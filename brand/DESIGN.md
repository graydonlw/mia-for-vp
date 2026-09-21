---
version: 0.1
name: Mia for VP
prefix: mv
description: "Pink-white and blush fields, one true-pink accent that carries every interactive job, Fredoka headlines and Nunito body, 24px card corners with fully round buttons and badges, and one signature detail: the petal pill that sits behind a single word per headline."
source: "Interview with Graydon on 2026-09-20 (personality: warm, optimistic, confident; register: light-first; direction B-Round, Fredoka). Calvary Chapel Academy's own colours were read live from ccobacademy.com and deliberately not used; both sit in color.retired. Mia's last name, election date, platform copy and photos are not yet supplied."
colors:
  plum: "#3B1D2B"
  rose: "#BE4C78"
  rose-deep: "#992D56"
  mid-rose: "#E58CAF"
  petal: "#F3C6DA"
  blush: "#FBE7F0"
  shell: "#FFF9FB"
  white: "#FFFFFF"
  gray-1: "#F6EEF1"
  gray-2: "#EBD3DE"
  gray-3: "#C9B2BC"
  gray-4: "#7D5A68"
  gray-5: "#56303F"
  field-light: "#FFF9FB"
  field-tint: "#FBE7F0"
  field-dark: "#3B1D2B"
  title-on-light: "#3B1D2B"
  title-on-dark: "#FFFFFF"
  body-on-light: "#6B4A58"
  body-on-dark: "#C9B2BC"
  muted: "#7D5A68"
  primary: "#BE4C78"
  primary-hover: "#992D56"
  on-primary: "#FFFFFF"
  link: "#992D56"
  link-on-dark: "#F3C6DA"
  line-light: "#EBD3DE"
  line-dark: rgba(255,255,255,.16)
  card-light: "#FFFFFF"
  card-dark: rgba(255,255,255,.06)
  focus: "#992D56"
  success: "#276B50"
  warning: "#855C10"
  danger: "#A33232"
  petal-ink: "#992D56"
  fill-light: rgba(59,29,43,.05)
  fill-dark-hover: rgba(255,255,255,.12)
  blob: "#FBE7F0"
  icon-tile: "#FBE7F0"
  icon-tile-alt: "#FFFFFF"
  input-field: "#FFFFFF"
  disabled-ink: "#A8929B"
  skeleton-shine: rgba(255,255,255,.65)
retired-colors: ["#0000B6", "#1E2A8A", "#2E1F26", "#2F7D5E", "#3D2B33", "#7A3550", "#856573", "#8E2F55", "#9A6B14", "#A63E67", "#A8536E", "#B33A3A", "#C2537E", "#D28FA6", "#E07A9E", "#E3C7D3", "#E9C4CF", "#F6E7E9", "#F7F6F2", "#FBF6F3"]
fonts:
  head: Fredoka
  body: Nunito
  mono: Space Mono
typography:
  display:
    font: head
    size: 72px
    weight: 600
    lineHeight: 1.02
    letterSpacing: -0.015em
  h1:
    font: head
    size: 46px
    weight: 600
    lineHeight: 1.08
    letterSpacing: -0.01em
  h2:
    font: head
    size: 34px
    weight: 600
    lineHeight: 1.15
    letterSpacing: -0.01em
  h3:
    font: head
    size: 26px
    weight: 500
    lineHeight: 1.25
  h4:
    font: head
    size: 22px
    weight: 500
    lineHeight: 1.3
  h5:
    font: head
    size: 19px
    weight: 500
    lineHeight: 1.35
  lede:
    font: body
    size: 20px
    weight: 400
    lineHeight: 1.6
  body:
    font: body
    size: 16px
    weight: 400
    lineHeight: 1.65
  small:
    font: body
    size: 14px
    weight: 400
    lineHeight: 1.6
  caption:
    font: body
    size: 13px
    weight: 400
    lineHeight: 1.5
  button:
    font: body
    size: 15px
    weight: 700
    lineHeight: 1.0
    letterSpacing: 0.01em
  badge:
    font: body
    size: 12px
    weight: 700
    lineHeight: 1.0
    letterSpacing: 0.06em
    transform: uppercase
  overline:
    font: mono
    size: 11px
    weight: 400
    lineHeight: 1.4
    letterSpacing: 0.16em
    transform: uppercase
  credit:
    font: mono
    size: 12px
    weight: 400
    lineHeight: 1.4
    letterSpacing: 0.08em
    transform: uppercase
rounded:
  default: 24px
  sm: 12px
  button: 999px
  input: 16px
  pill: 999px
  tile: 999px
  photo: 140px 140px 24px 24px
spacing:
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 40px
  2xl: 64px
  3xl: 96px
layout:
  container: 1120px
  gutter: 24px
  section-y: 96px
  nav-height: 72px
  measure: 66ch
  breakpoints:
    sm: 640px
    md: 820px
    lg: 1024px
    xl: 1280px
elevation:
  none: none
  card: none
  sticky: 0 -1px 0 var(--mv-plum-20)
motion:
  fast: 140ms
  base: 240ms
  ease: cubic-bezier(.2,.8,.2,1)
icons:
  grid: 24px
  stroke: 2px
  linecap: round
  linejoin: round
proportion:
  shell: 0.36
  white: 0.22
  blush: 0.14
  petal: 0.1
  rose: 0.09
  plum: 0.07
  mid-rose: 0.02
---

# Mia for VP Design System

The spec an agent reads before building any screen. Front matter above is generated from
`tokens/tokens.json` — never edit it by hand; run `build_tokens.py` instead. Everything below is
prose for judgment. Where the two could disagree, the tokens win.

Bracketed text like `[election day]` is a placeholder for a fact nobody has supplied yet. Leave it
bracketed. Do not invent a promise, a date, a number or a quote for this campaign.

---

## Overview

**Mia is running for Vice President of Calvary Chapel Academy, and this is her campaign site: one
short, warm, unmistakably personal page that tells students who she is and what she will do.**
*(Working positioning line — the final wording waits on the messaging pass.)*

**Distance read.** From across a hallway, on a phone held by someone walking: a soft pink page, one
very large rounded headline with a single word in a pink pill, and one pink button. Nothing else
competes.

**The one idea: soft, round and pink — a campaign that looks like a person, not an institution.**
Every rule below ladders to it:

- Nothing has a hard corner. Cards are 24px, buttons and badges are fully round, portraits sit in
  an arch. A square corner anywhere reads as a school form.
- Nothing shouts. Headlines get their weight from size, not from heavy type or capitals.
- The brightest color on the page sits on something you are meant to press. Rose is the only
  saturated color, and it means "interactive".
- Warmth comes from field color, not decoration. Even the white is pink (`#FFF9FB`).

**Personality:** Warm · Optimistic · Confident.

**The governing rule.** *One accent, one mark, one dark band.* Rose is the only interactive color,
the petal pill appears once per headline, and plum appears only in the footer. When something feels
flat, the fix is more space or a band change — never another color.

**Signature detail.** `.mv-mark`: a petal pill behind exactly one word per headline. It is how a
stranger recognizes two pages as the same campaign, and it is cheap — one span, no image.

---

## Story and Messaging

The messaging spine. **Rows marked OPEN are decisions Graydon has not made; rows in brackets are
facts nobody has supplied.** Do not fill either from imagination.

| Element | Content |
|---|---|
| Positioning | Mia for Vice President, Calvary Chapel Academy. |
| Promise | [What Mia commits to do in the role — in her words.] |
| Tagline | OPEN. "I won't go M.I.A." exists and is liked; whether the site leads with it is undecided (2026-09-20). |
| Definition | A student-government campaign site for one candidate, one election. |
| Proof | [Any role, year or number that shows she does what she says — student council, a club she started, an event she ran.] Use `—` and "to confirm" in the UI until supplied. |
| Ask | Vote for Mia on [election day], at [where and how students vote]. |

**The rule about numbers.** A stat block with an invented number is worse than no stat block. Ship
`—` with the caption "to confirm" (the preview does exactly this) until Mia supplies the real one.

---

## Voice and Language

Mia is 17 and writing to people she sees every day. The voice is hers, not a press office's.

| Move | Example | Rule and why |
|---|---|---|
| Say the thing plainly | "Here's what I'll actually do." | No throat-clearing. Students scroll; the promise goes in the first line or it is not read. |
| Specific over sweeping | "[One concrete change]" beats "a better school year" | A specific promise is checkable, which is the entire argument for voting for her. |
| First person, active | "I'll ask you first." | "It is proposed that…" is a school letter. She is a person asking. |
| Warm, never cutesy | "Tell her anything." | Friendly is the brand; baby talk is not. If it would embarrass her to say out loud, cut it. |
| Short sentences | 12–18 words | The type is large and round; long sentences look heavy in it. |

**Do:** sentence case everywhere · contractions · "you" and "I" · one idea per paragraph · name the
date and the place for voting on every page.

**Don't:** exclamation marks in headlines (one per page anywhere, at most) · ALL CAPS for emphasis
(that is what the mark is for) · slogans stacked on slogans · promises she cannot keep as VP ·
"vote for me because it would mean a lot" — the ask is about them, not her.

**Exact casing.** "Mia for VP" (the site's name). "Vice President" spelled out in body copy, "VP"
allowed in the wordmark, nav and buttons. "Calvary Chapel Academy" in full on first use, "CCA"
after. Never "MIA" in all caps except inside the slogan, where the periods are part of it: "M.I.A."

---

## Logo

There is no symbol and no logo file. The mark is **a wordmark set in type**, which is the right
answer for a two-week campaign: nothing to commission, nothing to license, and it can be typed.

| Version | Use | Spec |
|---|---|---|
| Primary wordmark | Nav, footer, anywhere the campaign signs its name | "Mia for VP" — Fredoka 600, `--mv-fs-h4` (22px), `--mv-title-on-light`, tracking `-0.005em` |
| Marked wordmark | One per page maximum, usually the footer | "Mia for **VP**" with `.mv-mark` on "VP" |
| Short form | Favicon, sticker, profile picture | "M" in Fredoka 600, white on `--mv-primary`, in a `--mv-radius-tile` circle |

- **Clear space:** one cap-height of Fredoka on every side. In the nav that is the `--mv-space-md`
  gap already in the CSS.
- **Minimum size:** 18px type height for the wordmark; 28px square for the short form. Below that
  Fredoka's round terminals fill in.
- **On color:** on shell, blush or white → `title-on-light`. On plum → `title-on-dark`. On rose →
  `on-primary`. Never rose type on blush: 6.21:1 passes, but it makes the wordmark look like a link.

**Don't:** stretch, rotate or outline it · set it in any face but Fredoka · put it on a photo
without a solid field behind it · add a tagline lockup (the tagline is undecided) · use the
school's crest or name-mark anywhere — this is Mia's campaign, not a school publication.

---

## Colors

One accent. Most of the page is field; the only saturated color is the one you press.

### Brand

| Name | Hex | Job |
|---|---|---|
| shell | `#FFF9FB` | The default page field. A pink-white, so the page reads warm rather than clinical. |
| blush | `#FBE7F0` | Alternating band field, decorative circles, soft cards. |
| petal | `#F3C6DA` | The signature pill behind a headline word, badges, the photo arch, icon tiles. |
| mid-rose | `#E58CAF` | Mid tone for charts, illustration and dividers. **Never a text color and never a text field.** |
| rose | `#BE4C78` | The interactive color: primary buttons, focus ring, first chart series. |
| rose-deep | `#992D56` | Links, hover fill, and text sitting on petal or blush. |
| plum | `#3B1D2B` | Ink for headings, and the single dark field — the footer. |

### Neutral ramp

| Name | Hex | Job |
|---|---|---|
| white | `#FFFFFF` | Card field on shell and blush bands; titles in the footer. |
| gray-1 | `#F6EEF1` | Disabled fills, skeleton blocks. |
| gray-2 | `#EBD3DE` | Borders and dividers on light. |
| gray-3 | `#C9B2BC` | Paragraph text in the footer. |
| gray-4 | `#7D5A68` | Captions, labels, placeholders on light. |
| gray-5 | `#56303F` | Panel and hover fill inside the footer. |

Every gray is warm — they carry a little of the plum hue, so nothing on the page looks like a
default browser gray next to the pink.

### Text roles

| Role | On light | On plum |
|---|---|---|
| Heading | `title-on-light` `#3B1D2B` | `title-on-dark` `#FFFFFF` |
| Paragraph | `body-on-light` `#6B4A58` | `body-on-dark` `#C9B2BC` |
| Muted / caption | `muted` `#7D5A68` | `body-on-dark` `#C9B2BC` |
| Link | `link` `#992D56` | `link-on-dark` `#F3C6DA` |
| On rose fill | `on-primary` `#FFFFFF` | — |

**Paragraph text never sits at pure black or pure white.** `#6B4A58` on shell is 7.36:1 — plenty —
and it keeps body copy from out-shouting the headline, which is the whole hierarchy in a system
with one weight step.

### Tints

Allowed levels: **80 / 60 / 40 / 20%** of rose, petal, mid-rose and plum (`--mv-rose-80` …).

Tints are for fills, hover states, chart layers and decorative shapes. **Never set text on a tint**,
because a tint's contrast depends on what is behind it and no tint in this kit clears 4.5:1 against
shell. Text on a soft field uses the solid `field-tint` with `petal-ink`, which is 6.21:1.

### Proportion

Target share of a typical screen. This one row is the defence against a page that turns into a
rainbow:

| shell | white | blush | petal | rose | plum | mid-rose |
|---|---|---|---|---|---|---|
| 36% | 22% | 14% | 10% | 9% | 7% | 2% |

Fields (shell + white + blush) are 72%. If rose is over ~10% of a screen, something that should be
a link or a field has become a button.

### Gradients

**None.** This brand is flat color on flat color. A gradient here would fight the round shapes for
attention and is the fastest way to make a hand-made site look like a template. If one is ever
needed, it gets defined here with exact stops first.

### Retired

These must never come back. `lint_kit.py` reports them first and loudest:

`#0000B6` `#1E2A8A` `#2E1F26` `#2F7D5E` `#3D2B33` `#7A3550` `#856573` `#8E2F55` `#9A6B14` `#A63E67`
`#A8536E` `#B33A3A` `#C2537E` `#D28FA6` `#E07A9E` `#E3C7D3` `#E9C4CF` `#F6E7E9` `#F7F6F2` `#FBF6F3`

Two groups: the dustier "Petal Poster" palette this kit replaced on 2026-09-20 when the direction
moved pinker, and **Calvary Chapel Academy's own colors** (`#0000B6`, `#F7F6F2`), which are retired
on purpose — borrowing school livery would imply the school endorses the candidate.

### Rules

**Do:** use rose for anything clickable and nothing else · put deep-rose text on petal and blush
fills · change the field to create a section, not the accent · keep one rose button per view — the
one you most want pressed · use petal for the mark, badges, tiles and the arch.

**Don't:** set white text on petal (1.51:1) or mid-rose (2.41:1) — *the two banned pairs in this
kit* · lighten rose: `#BE4C78` with white is 4.67:1, which is the ceiling · use rose as a large
field behind body copy · introduce a second accent hue "for variety" · reach for a school color.

### Contrast

Generated with `python3 scripts/contrast.py brand/` on 2026-09-20. The script pairs every text role
against every field, including combinations this brand never produces (a link inside the footer's
panel fill, say). The rows below are the pairs that **can** occur:

| Text | on Field | Ratio | AA normal (4.5) | AA large (3.0) |
|---|---|---|---|---|
| title-on-dark `#FFFFFF` | field-dark `#3B1D2B` | 15.04 | Pass | Pass |
| title-on-light `#3B1D2B` | white `#FFFFFF` | 15.04 | Pass | Pass |
| title-on-light `#3B1D2B` | field-light `#FFF9FB` | 14.46 | Pass | Pass |
| title-on-light `#3B1D2B` | field-tint `#FBE7F0` | 12.74 | Pass | Pass |
| title-on-light `#3B1D2B` | gray-2 `#EBD3DE` | 10.67 | Pass | Pass |
| link-on-dark `#F3C6DA` | field-dark `#3B1D2B` | 9.95 | Pass | Pass |
| title-on-light `#3B1D2B` | petal `#F3C6DA` | 9.95 | Pass | Pass |
| body-on-light `#6B4A58` | white `#FFFFFF` | 7.65 | Pass | Pass |
| body-on-dark `#C9B2BC` | field-dark `#3B1D2B` | 7.57 | Pass | Pass |
| body-on-light `#6B4A58` | field-light `#FFF9FB` | 7.36 | Pass | Pass |
| link `#992D56` | white `#FFFFFF` | 7.33 | Pass | Pass |
| link `#992D56` | field-light `#FFF9FB` | 7.05 | Pass | Pass |
| on-primary `#FFFFFF` | danger `#A33232` | 6.86 | Pass | Pass |
| body-on-light `#6B4A58` | field-tint `#FBE7F0` | 6.48 | Pass | Pass |
| on-primary `#FFFFFF` | success `#276B50` | 6.35 | Pass | Pass |
| title-on-light `#3B1D2B` | mid-rose `#E58CAF` | 6.23 | Pass | Pass |
| link / petal-ink `#992D56` | field-tint `#FBE7F0` | 6.21 | Pass | Pass |
| muted `#7D5A68` | field-light `#FFF9FB` | 5.71 | Pass | Pass |
| muted `#7D5A68` | field-tint `#FBE7F0` | 5.03 | Pass | Pass |
| petal-ink `#992D56` | petal `#F3C6DA` | 4.85 | Pass | Pass |
| on-primary `#FFFFFF` | primary `#BE4C78` | 4.67 | Pass | Pass |
| on-primary `#FFFFFF` | mid-rose `#E58CAF` | 2.41 | **Fail** | **Fail** |
| on-primary `#FFFFFF` | petal `#F3C6DA` | 1.51 | **Fail** | **Fail** |

Takeaways an agent should carry:

1. **Every pairing this brand produces passes AA.** There are no documented exceptions and no
   "large text only" escapes — which is unusual, and worth not breaking.
2. **Rose is at its ceiling.** White on `#BE4C78` is 4.67:1. Any lighter rose needs dark text on the
   button instead, which changes the whole button spec. Do not nudge it.
3. **The last two rows are rules, not failures.** White never sits on petal or mid-rose. Those
   fields carry `petal-ink` (`#992D56`, 4.85:1 on petal).
4. **Muted text has one home:** shell (5.71:1) and blush (5.03:1). On the `gray-2` border color it
   drops to 4.22:1, so captions never sit on a divider fill.

---

## Typography

**Fredoka does the headlines, Nunito does everything you actually read, and Space Mono does the
small structural labels.** Fredoka's rounded terminals are the type half of the one idea; Nunito's
slightly rounded shapes match it without getting in the way of a paragraph; Space Mono's uppercase
overlines give the soft page enough structure to look designed rather than merely pleasant.

**Weight policy: Fredoka at 600 for display/h1/h2 and 500 for h3–h5; Nunito at 400 for everything
you read, with 700 reserved for buttons, badges, labels and nav links.** Hierarchy comes from size
and space, never from a heavier headline. Never mix weights inside one text block.

### The ramp

| Style | Face | Size / line height | Tracking | Notes |
|---|---|---|---|---|
| display | Fredoka 600 | 72 / 1.02 | -0.015em | Hero only. `clamp(40px, 8vw, 72px)`; max 14ch. |
| h1 | Fredoka 600 | 46 / 1.08 | -0.01em | Page titles. `clamp(32px, 6vw, 46px)`. |
| h2 | Fredoka 600 | 34 / 1.15 | -0.01em | Section titles. `clamp(26px, 4.5vw, 34px)`. |
| h3 | Fredoka 500 | 26 / 1.25 | — | Sub-sections, CTA headings. |
| h4 | Fredoka 500 | 22 / 1.30 | — | The wordmark size. |
| h5 | Fredoka 500 | 19 / 1.35 | — | Card titles. |
| lede | Nunito 400 | 20 / 1.60 | — | Hero subtitle and intros. Max 40ch. |
| body | Nunito 400 | 16 / 1.65 | — | Max `66ch`. |
| small | Nunito 400 | 14 / 1.60 | — | Card copy, table cells, nav links. |
| caption | Nunito 400 | 13 / 1.50 | — | Help text, photo captions. |
| button | Nunito 700 | 15 / 1.00 | 0.01em | Buttons and nav links. |
| badge | Nunito 700 | 12 / 1.00 | 0.06em | Uppercase. Badges and pills. |
| overline | Space Mono 400 | 11 / 1.40 | 0.16em | Uppercase. Eyebrows, table headers. |
| credit | Space Mono 400 | 12 / 1.40 | 0.08em | Uppercase. The footnote line, photo credits. |

Steps sit at roughly 1.2–1.3× apart, and the smallest headline (19px) is comfortably above body
(16px), so a card title always reads as a title.

### Loading

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;600&family=Nunito:wght@400;600;700&family=Space+Mono:wght@400;700&display=swap">
```

The same URL is `font.import` in tokens.json and is emitted at the top of `tokens.css`, so importing
the stylesheet is enough. `display=swap` is deliberate: text appears in the fallback immediately
rather than leaving a blank hero.

**Fallbacks:** `Trebuchet MS, Verdana, sans-serif` for Fredoka and Nunito — Trebuchet is the
roundest face on both Windows and macOS, so an email or Office surface degrades in the right
direction. `Courier New, monospace` for Space Mono.

### Caveat: parked, not adopted

The approved mock used **Caveat** (handwriting) on one word — "Vote *Mia*". It is not in the token
set: the generator emits three families, and a fourth is a real decision, not a default. To adopt
it: add `font.script` values to DESIGN.md and the import URL, add a `.mv-script` class, and add
"Caveat" to the linter's allowed fonts. Rules if adopted: **one or two words per page, never a
headline, never body copy, never below 24px**, always in `--mv-primary` or `--mv-rose-deep`.

### Rules

**Do:** sentence case · left-align everything except the hero and empty states · body at `66ch` ·
emphasis by size, space, or the mark · tabular numerals in stat numbers and tables.

**Don't:** all-caps running text (uppercase is for badges, overlines and credits only) · a second
display face · bold Nunito for emphasis inside a paragraph — use the mark or a new line · type over
a photo without a solid field · letter-spacing on body copy · headlines under 26px, which makes
Fredoka look like a UI label.

---

## Layout

### Band rhythm

Sections alternate by field, never by accent. A page reads: nav (shell) → hero (shell, with blobs) →
tint → shell → tint → CTA → footer (plum).

| Band | Class | Field | Use |
|---|---|---|---|
| Light | `.mv-band-light` | shell `#FFF9FB` | Default. Hero, about, anything that leads. |
| Tint | `.mv-band-tint` | blush `#FBE7F0` | Every other section, so the page has rhythm without a second color. |
| Dark | `.mv-band-dark` / `.mv-footer` | plum `#3B1D2B` | **The footer, and nothing else.** |

Two light bands never touch: if two consecutive sections both want shell, one becomes tint or gets a
white card grid to break it.

### Numbers

| Thing | Value |
|---|---|
| Container | 1120px |
| Gutter | 24px (drops to 16px below 820px) |
| Section padding (y) | 96px (`--mv-space-3xl`); 64px below 820px |
| Nav height | 72px, sticky |
| Body measure | 66ch |
| Card grid | `repeat(auto-fit, minmax(min(280px, 100%), 1fr))`, 16px gap |
| Two-column | `1fr 1fr`, 64px gap; collapses to one column at 820px |
| Space scale | 8 · 12 · 16 · 24 · 40 · 64 · 96 |

Breakpoints: **sm 640 · md 820 · lg 1024 · xl 1280.** Only `md` does real work: nav links hide, the
two-column block stacks, the container loses padding, and the sticky vote bar appears.

No horizontal scroll at 320px. The display style is clamped and headline words are allowed to break
(`overflow-wrap: anywhere`), because "Vice President" does not fit on a narrow phone otherwise.

---

## Elevation and Depth

**Flat. There are no shadows on this site.** Depth is made, in this order:

1. **Band change** — the main tool. A section is a new field color.
2. **A card on a band** — white card on blush, or blush card on white.
3. **A 1px `line-light` border** — the quietest separation.
4. **Space** — 96px between sections does more than any shadow.

The one exception is `--mv-shadow-sticky` (`0 -1px 0 var(--mv-plum-20)`) under the mobile vote bar,
because a bar floating over scrolling content needs an edge to read as fixed. A shadow anywhere else
is a bug: round corners plus drop shadows is the exact look this brand is avoiding.

---

## Shapes

Roundness is the brand. Radius is assigned per element class, so nothing is arbitrary:

| Element | Token | Value |
|---|---|---|
| Cards, alerts, CTA bands, panels | `--mv-radius-default` | 24px |
| Small chips, focus outlines on links | `--mv-radius-sm` | 12px |
| Buttons, badges, the mark, blobs | `--mv-radius-button` / `-pill` | 999px |
| Inputs, selects, textareas | `--mv-radius-input` | 16px |
| Icon tiles, round portraits | `--mv-radius-tile` | 999px |
| Portrait frame (the arch) | `--mv-radius-photo` | `140px 140px 24px 24px` |

**The arch** is the one piece of shape language that is not just a radius: a portrait with a fully
round top and square-ish base, on a petal field. It is what makes a photo of a 17-year-old look
deliberate rather than cropped.

**Blobs** (`.mv-blob`) are petal or blush circles behind a band. Rules: at most two per band, always
`aria-hidden`, never behind body text, never over a photo, and the band clips them
(`.mv-has-blobs` sets `overflow: hidden`).

Square corners appear nowhere. If a component needs one, it is the wrong component.

---

## Motion

| Token | Value | Use |
|---|---|---|
| `--mv-motion-fast` | 140ms | Color, border and transform on hover, focus, press. |
| `--mv-motion-base` | 240ms | Anything that moves more than a few pixels. |
| `--mv-motion-ease` | `cubic-bezier(.2,.8,.2,1)` | Everything. One curve, so the whole site moves the same way. |

**Animates:** button and link hover, focus rings, the link arrow (3px right), the loading spinner,
the skeleton shimmer. **Never animates:** page or section entrances, headline reveals, parallax,
counters that tick up, anything triggered by scroll. A five-section campaign page that animates on
scroll reads as a template.

`prefers-reduced-motion: reduce` sets every duration to 0ms globally — already in the component CSS,
do not override it per component.

---

## Components

Every color and font below is a token. Every interactive component ships all eight states:
**default · hover · focus-visible · active · disabled · loading · error · success**, and the CSS
carries `.is-hover`, `.is-focus`, `.is-active`, `.is-disabled`, `.is-loading`, `.is-error`,
`.is-success` so `preview/index.html` can show them at once. Focus is never removed.

### The mark — `.mv-mark` (signature detail)

A petal pill behind **one word per headline**.

| Variant | Fill | Text | Use |
|---|---|---|---|
| `.mv-mark` | `petal` | `title-on-light` (9.95:1) | The default. One per headline. |
| `.mv-mark--solid` | `primary` | `on-primary` (4.67:1) | The footer wordmark, or one hero per site. Never both in one view. |

Padding `0.04em 0.34em`, radius `pill`, `box-decoration-break: clone` so it survives a line wrap.
**Rules:** one mark per headline — two means neither word matters; never on a word that wraps
mid-word; never on more than three words; never inside body copy.

### Nav — `.mv-nav`

Sticky, 72px tall, shell field, 1px `line-light` bottom border, wordmark left, links + one button
right. Links are `small` at weight 700 in `body-on-light`, hover `link`, and the current page gets
`aria-current` (2px underline at `link`, 6px offset). **Below 820px every link except the button
hides** — the sticky bar carries the ask instead. Focus ring: 2px `focus`, 4px offset.

### Hero — `.mv-hero`

| Variant | Field | Use |
|---|---|---|
| `.mv-hero` | shell | Default. |
| `.mv-hero--tint` | blush | When the section under it is shell. |

Padding 96px top and bottom, display headline capped at 14ch, `.mv-sub` lede at 40ch, buttons 40px
below. At most one decorative device: two blobs **or** one portrait, never both. There is **no dark
hero** in this brand — a plum hero would make the page a poster, and the one idea says person.

### Buttons — `.mv-btn`

| Variant | Fill | Text | Border | Hover | Where |
|---|---|---|---|---|---|
| `--primary` | `primary` | `on-primary` | none | `primary-hover` | One per view: the thing you most want pressed. |
| `--secondary` | transparent | `title-on-light` | 1.5px `line-light` | `fill-light`, border `muted` | Beside a primary. |
| `--soft` | `field-tint` | `petal-ink` | none | `petal` | Third action, or a button on a white card. |
| `--ghost` | none | `link` | none | underline | Inline, low emphasis. Cancel. |
| `--danger` | `danger` | `on-primary` | none | darker | Destructive confirm only. |

Sizes: min-height **48px** (44px ghost, 40px `--sm`), padding `0 24px`, radius `pill`, type `button`
(Nunito 700, 15px). Gap between adjacent buttons: 12px. Icon before the label, 20px, 8px gap.

States: hover changes fill only · active adds `translateY(1px)` · focus-visible is a 2px `focus`
ring at 3px offset · disabled is `gray-1` with `disabled-ink` and `cursor: not-allowed` · loading
hides the label and spins an 18px ring · error and success swap the fill to `danger` / `success`.

**Traps:** never two primaries in one view · never a rose button on a petal or mid-rose field (the
edge disappears) · never change the radius — pill is the shape, everywhere.

### Links — `.mv-link`

`link` `#992D56`, underlined at 1.5px with a 3px offset, thickening to 2.5px on hover; weight 700.
In the footer, `link-on-dark` (petal, 9.95:1) with no underline until hover. `.mv-link--plain` drops
the underline for nav-like lists. `.mv-arrow` slides 3px right on hover.

**Why deep rose and not rose:** `#BE4C78` on shell is 3.6:1 and fails at body size. The link color
is deliberately one step darker than the button fill.

### Cards — `.mv-card`

| Variant | Field | Border | Where |
|---|---|---|---|
| `.mv-card` | `card-light` (white) | 1px `line-light` | On shell bands. |
| `.mv-card--soft` | `field-tint` | none | Mixed into a grid for rhythm, or on white. |
| In `.mv-band-tint` | white | none — the field does the separating | On blush bands. |
| In `.mv-band-dark` | `card-dark` | 1px `line-dark` | Footer only. |

Padding 24px, radius 24px, title `h5` (Fredoka 500, 19px), body `small`. Grid:
`auto-fit, minmax(min(280px,100%), 1fr)`, 16px gap — three across at container width, one on a
phone. Icon tile (`.mv-tile`) is a 48px circle: blush on white cards, white on blush cards, with a
`petal-ink` Lucide icon. **The card's own fill decides the tile, not the band it sits in** — keying
it to `.mv-band-tint` puts a white tile on a white card, where it disappears.

Cards look identical on both light bands by design. **Do not add a shadow to lift them.**

### Photo — `.mv-photo`

| Variant | Shape | Ratio | Use |
|---|---|---|---|
| `.mv-photo` | the arch | 4:5 | Portraits of Mia. The default. |
| `.mv-photo--round` | circle | 1:1 | Small avatars beside a quote. |
| `.mv-photo--card` | 24px radius | 3:2 | Events, groups, anything not a portrait. |

The frame's background is `petal`, so a missing or slow image leaves a deliberate pink shape rather
than a hole. `.mv-photo-frame` allows one badge pinned to the bottom edge.

### Badges — `.mv-badge`

Uppercase `badge` type (Nunito 700, 12px, 0.06em), padding `7px 14px`, radius pill. Default is
petal + `petal-ink`; `--soft` is blush + `petal-ink`; `--solid` is rose + white. Status variants mix
their color at 12–16% with white and set the text in the status color. **Never white text on a
badge that is not `--solid`.**

### Alerts — `.mv-alert`

Icon + bold first line + body, in a card-radius box with a 1px border and a status-tinted field at
8–10%. Four kinds: info (rose icon), success, warning, danger. The field is always near-white — four
saturated alert fields would out-colour the page.

### Forms — `.mv-field`

Inputs are 48px min-height, 12px/16px padding, white field, 1.5px `line-light` border, 16px radius.
Hover darkens the border to `muted`. Focus: border `focus` plus a 3px ring at 25% `focus` — the
default outline is replaced, not removed. Error sets the border to `danger` and the help text to
`danger`; success does the same in green. Disabled is `gray-1` with `disabled-ink`. Checkboxes are
20px with `accent-color: primary` in a 44px-tall label.

**Never use a placeholder as the label** — every field keeps a visible `.mv-label`, because a
placeholder disappears the moment someone types.

### Stats — `.mv-stat`

`--card` (blush) and `--primary` (rose, white numbers) variants. Number in `h1` Fredoka with
tabular numerals; caption in `small`. **Ship `—` and "to confirm" until Mia supplies a real
number** — the preview does exactly this, on purpose.

### Quote — `.mv-quote`

A 3px petal rule above the quote, `h4` in Fredoka 500, attribution in `small` `muted`.
`--soft` swaps the rule for a blush card. No quotation-mark graphics, no italics, no photo inside
the quote.

### CTA — `.mv-cta` and `.mv-sticky-cta`

`.mv-cta` is a blush band-within-a-band: heading, one line, one button, 24px radius. **On a blush
band it becomes a white card** (`.mv-band-tint .mv-cta`), because blush on blush has no edge. `--solid`
fills it rose with white text — **one per page, and never adjacent to a rose button**. Below 820px
`.mv-sticky-cta` pins two buttons to the bottom edge with a safe-area inset. It is the only element
in the kit with a shadow.

### Footer — `.mv-footer`

The only plum field. Wordmark, one line of text, links in `link-on-dark`, and `.mv-footnote` — a
Space Mono credit row above a `line-dark` border. Secondary buttons here take `line-dark` and white
text automatically via `.mv-band-dark`.

### Empty and loading — `.mv-empty`, `.mv-skeleton`

Empty: 1.5px dashed `line-light`, centered `muted` text, one ghost link. Skeleton: a blush block
with a white shimmer sweeping over 1.4s, stopped by reduced-motion.

### Table — `.mv-table`

Space Mono uppercase headers, 1px row borders, blush on row hover, numbers right-aligned and
tabular in `.mv-value`. Wrapped in `.mv-table-wrap` so it scrolls horizontally on a phone instead of
breaking the page.

### Not yet specified

- **Tabs** — not needed by the first screen. If one appears: card border, 2px `primary` indicator
  under the active tab, `button` type.
- **Modals and drawers** — not needed. If one appears: white field, 24px radius, plum scrim at 50%,
  no shadow (the scrim is the depth), close button top-right at 44px.

Both are placeholders on purpose. Building one silently means inventing a component the spec does
not cover — add it here first.

---

## Icons

**Lucide**, the library's current release, used as inline SVG so `currentColor` works.

| Property | Value |
|---|---|
| Grid | 24×24 (`--mv-icon-grid`) |
| Stroke | 2px (`--mv-icon-stroke`) — matches Fredoka's round weight |
| Caps and joins | round, round |
| Sizes | 24px default, 20px (`.mv-icon--sm`) inside alerts and buttons |
| Colors | `petal-ink` in tiles, `primary` in alerts, `currentColor` everywhere else |

**Rules:** one color per icon · never two libraries in one project · never decorative icons beside
every heading — an icon earns its place by labelling something · always `aria-hidden="true"` when a
text label sits beside it, and `aria-label` on an icon-only button · never fill an outline icon.

---

## Data Visualization

Charts are unlikely on a campaign site, but a poll result or a "what students asked for" breakdown
would be. The order is fixed so nothing invents its own palette:

- **Categorical:** `rose` → `mid-rose` → `plum` → `petal` → `rose-deep`. Two series stop at the
  first two.
- **Sequential:** rose tints, `--mv-rose-20` → `--mv-rose-80` → `rose`.
- **Diverging:** `rose` ← `blush` neutral midpoint → `plum`.
- **Gridlines:** 1px `line-light`, horizontal only, no vertical grid, no border box.
- **Labels:** `caption` in `muted`; values in `small` with tabular numerals.

**Never:** text on a tint or on `mid-rose` · a legend where a direct label would fit · a pie chart
with more than three slices · a chart without its source line in `credit` type.

---

## Imagery

Real photos of Mia, taken by someone she knows — not stock, not AI, not a school portrait if a
candid exists. The whole point of the brand is that it looks like a person.

**Do:** shoot in daylight against a plain wall · frame head-and-shoulders for the arch's 4:5 crop ·
keep her looking at the camera in the hero · use one photo per section at most · run photos at full
width of their column with `object-fit: cover`.

**Don't:** put type over a photo (the kit has no scrim, and adding one is a decision, not a
default) · use a photo behind a whole band · apply a pink wash or any filter — the frame carries the
brand color, the photo stays honest · crop a portrait to a square when the arch is available · use
a photo of other students without asking them.

**When there is no photo:** the petal arch stands on its own as a shape, or the section uses a card
grid. Never a stock placeholder person; never a gray box.

---

## Assets

| What | Where | Notes |
|---|---|---|
| Tokens | `brand/tokens/` | `tokens.json` is the source; the other four files are generated. |
| Components | `brand/css/mia-for-vp.css` | Requires `tokens.css` first. |
| Preview | `brand/preview/index.html` | Open in a browser; it is the visual test. |
| Icons | `brand/icons/` | Currently empty — Lucide is used from source, nothing vendored yet. |
| Photos | `brand/assets/` | Not yet supplied. Name them `mia-<context>-<n>.jpg`, keep under 400KB, export at 1600px on the long edge. |
| Fonts | Google Fonts CDN | Self-host later by downloading the three families (all OFL) into `brand/assets/fonts/` and swapping `font.import`. |

Permissions: photos of anyone but Mia need that person's OK before they go on a public site.

---

## Companion Files

| File | What it is |
|---|---|
| `brand/DESIGN.md` | This file. The spec. |
| `brand/brief.md` | Interview answers, assumptions still to confirm, and what is still open. |
| `brand/tokens/tokens.json` | **The source of truth for every value.** |
| `brand/tokens/tokens.css` | Generated — `--mv-*` custom properties, with the font import. |
| `brand/tokens/tailwind.preset.js` | Generated — for a Tailwind build. |
| `brand/tokens/tokens.js` | Generated — `window.BRAND_TOKENS`, used by the preview. |
| `brand/tokens/front-matter.yaml` | Generated — spliced into this file's front matter. |
| `brand/css/mia-for-vp.css` | The components, as CSS. |
| `brand/preview/index.html` | Every token and component on one page, all button states forced. |
| `brand/README.md` | How to rebuild and how to wire the kit into an app. |

Rebuild after any token edit:

```bash
python3 ~/.claude/skills/brand-kit/scripts/build_tokens.py brand/ --design DESIGN.md
```

---

## Do's and Don'ts (quick reference)

An agent about to ship a screen should be able to check it against this list alone.

**Do**

1. Read `tokens.json` for values; read this file for judgment.
2. Keep one rose button per view — the action you most want taken.
3. Put exactly one `.mv-mark` in a headline, on the word that carries the meaning.
4. Alternate bands shell → blush → shell; let the field make the section.
5. Set deep-rose text (`petal-ink`) on every petal or blush fill.
6. Give portraits the arch, and every decorative circle `aria-hidden`.
7. Leave unknown facts bracketed: `[election day]`, `—` with "to confirm".
8. Keep body copy at `66ch` and never at pure black.
9. Ship all eight button states, focus ring included.
10. Run the linter over `src/` before committing.

**Don't**

1. Put white text on petal (1.51:1) or mid-rose (2.41:1) — the two banned pairs.
2. Lighten rose: 4.67:1 is the ceiling for a white-text button.
3. Add a shadow to anything but the mobile sticky bar.
4. Use a square corner anywhere.
5. Introduce a second accent, a gradient, or a school color.
6. Use plum as a field outside the footer.
7. Set text on a tint, or on top of a photo.
8. Animate anything on scroll.
9. Invent a platform promise, a number, a quote or a date.
10. Type a hex or a font name into a component file — add the token first.

---

## Changelog

| Date | Change |
|---|---|
| 2026-09-20 | Kit created. Direction B-Round chosen from three explored (Soft Glow, Petal Poster, Blush & School Blue) after a rounded-typeface study; Fredoka + Nunito + Space Mono; 43 colors, 14 type styles. |
| 2026-09-20 | Palette shifted pinker on request: cream/dusty-rose fields replaced by shell/blush/petal, accent and ink both replaced (old values now in the retired list). 20 hexes retired, including Calvary Chapel Academy's own blue and cream, which are retired deliberately. |
| 2026-09-20 | Caveat (handwriting accent) parked rather than adopted; conditions for adopting it recorded in § Typography. |
