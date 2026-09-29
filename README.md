# Danube Dusk

An immediately.run theme taken from the sky over the Danube just after sunset,
sampled from zenith to horizon:

`#4c5a6f` → `#6a798b` → `#8594a1` → `#b9c2c0` → `#e6ddb7` → `#f9e0a1` → `#ffc25b` → `#e8a85e`

- **Dusk** (dark, preferred): grounds are the zenith slate taken down into night; inks are the pale horizon band.
- **Dawn** (light): grounds are the cream and sage just above the horizon; inks are the zenith slate.
- **Accents** (shared): horizon amber `#c8742c` and evening slate `#66788e`, so the accent gradient runs from the horizon up the sky.

Every text pair clears AA (4.5:1) and every accent clears 3:1 on both modes' grounds, as checked by the host's load gates (HOST_THEMING_SPEC §6).

## Use it

Open immediately.run → platform menu → **Themes… → Add theme**, and open this repo.

## Layout

```
immediately.run.json              marker: { "kind": "theme" }
themes/danube-dusk/
  immediately.run.json            the bundle's marker
  theme.json                      manifest: id, label, modes
  theme.css                       theme-level tokens (accents)
  modes/light.css                 Dawn
  modes/dark.css                  Dusk
```

Mode files are token-only: custom-property declarations and comments, nothing else.
