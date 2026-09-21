# Mia for VP icons

Chosen set: (Lucide / Phosphor / Heroicons / custom), version: . Grid, stroke, caps and joins
are tokens (`--mv-icon-*`); the `.mv-icon` class applies them.

For a library: import it in the app and do not copy files here; list the allowed subset in
DESIGN.md "Icons" if the set is large. For a custom set: one SVG per icon in `svg/` using
`currentColor`, no fill, the token stroke, plus `manifest.json`:

```json
{ "grid": 24, "strokeWidth": 1.6, "icons": [ { "name": "Target", "slug": "target", "category": "Strategy", "file": "svg/target.svg" } ] }
```

Rules that hold either way: one color per icon, assigned by meaning; never decorative; never mix
libraries; scale the canvas, never the stroke.
