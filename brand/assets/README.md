# Mia for VP assets

Logos, fonts, imagery, and downloads. The payload is gitignored (see `.gitignore`); only
`*.json` manifests and this file are tracked, so record each asset's source URL, license, and
size cap in `manifest.json` and add a fetch script when the source is remote.

```
logos/     <name>-<horizontal|stacked|icon>-<color|black|white>.<png|svg>
fonts/     one folder per family with its license file
imagery/   photography and illustration, under 700KB each
```
