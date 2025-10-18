# Beamer Theme: joaquin

A reusable Beamer theme extracted from your existing slides (auto-extracted where possible).

## Files
- `beamertheme-joaquin.sty` — the theme (colors, fonts, frametitle, footline).
- `template_main.tex` — minimal example using the theme.

## Quick Start
```
pdflatex template_main.tex
pdflatex template_main.tex
```
If using `minted`, compile with:
```
pdflatex -shell-escape template_main.tex
pdflatex -shell-escape template_main.tex
```

## Customize
- Edit colors in the `.sty` file (`\definecolor`, `\setbeamercolor`).
- Adjust fonts with `\setbeamerfont` (defaults included).
- Replace the footline / frametitle templates by editing the template section.

> Optionally install to your local TeX tree at `~/texmf/tex/latex/beamertheme-joaquin/`.