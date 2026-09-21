# Mia for VP brand kit

The Mia for VP design system as code. Built with the `brand-kit` skill on 2026-09-20.

**Start with [`DESIGN.md`](DESIGN.md).** It is the whole spec (voice, color, type, layout,
components, icons, imagery) with machine-readable tokens in its front matter, so an AI coding
agent can build on-brand UI from that one file.

## Layout

```
DESIGN.md                  the spec + token front matter (front matter is generated)
tokens/tokens.json         THE source of truth for every value; edit this, never the files below
tokens/tokens.css          generated: --mv-* custom properties
tokens/tailwind.preset.js  generated: Tailwind preset
tokens/tokens.js           generated: window.BRAND_TOKENS for the preview page
tokens/front-matter.yaml   generated: the YAML block spliced into DESIGN.md
css/mia-for-vp.css         components (type, bands, nav, hero, buttons, cards, photo, badges,
                           alerts, forms, CTA, sticky vote bar, footer, empty/skeleton)
preview/index.html         every token and component on one page; open it after any change
icons/                     only if a Lucide icon is ever replaced
assets/                    photography of Mia (payload gitignored; manifests tracked)
```

## Working with it

```bash
# after editing tokens/tokens.json:
python3 ~/.claude/skills/brand-kit/scripts/build_tokens.py . --design DESIGN.md
open preview/index.html

# prove nothing drifted (run before committing UI work anywhere in the project):
python3 ~/.claude/skills/brand-kit/scripts/build_tokens.py . --check --design DESIGN.md
python3 ~/.claude/skills/brand-kit/scripts/lint_kit.py --tokens tokens/tokens.json css preview ../src
python3 ~/.claude/skills/brand-kit/scripts/contrast.py .
```

## Consuming the kit

```html
<link rel="stylesheet" href="tokens/tokens.css">
<link rel="stylesheet" href="css/mia-for-vp.css">
```

Tailwind: `presets: [require('./brand/tokens/tailwind.preset.js')]` then `bg-mv-primary`, `font-head`, `text-h2`.

Rules that hold everywhere: every color and font in UI code references a token; the preview page
must still look right after any change; `DESIGN.md` wins over taste.

DESIGN.md is deliberately not linted: its generated front matter lists the retired colors, which
the linter would report as uses of them.
