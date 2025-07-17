# Beckwitt CV

This repository contains the LaTeX source for David Beckwitt's curriculum vitae. All content is authored and maintained by David Beckwitt.

## Structure

- `cv-llt.tex` – single LaTeX source containing all CV content
- `sections/` – legacy section files kept for reference
- `bib/own-bib.bib` – bibliography entries used in publications section
- `images/` – profile photograph
- `settings.sty` – common style configuration

## Building

Compile `cv-llt.tex` using `pdflatex` or `latexmk`:

```bash
latexmk -pdf cv-llt.tex
```

