# Beckwitt CV

This repository contains the LaTeX source for my curriculum vitae. All content is authored and maintained by David Beckwitt.

## Structure

- `cv-llt.tex` – main document that assembles all CV sections
- `sections/` – individual TeX files for each CV section
- `bib/own-bib.bib` – bibliography entries used in publications section
- `images/` – profile photograph
- `settings.sty` – common style configuration

## Building

Compile `cv-llt.tex` using `pdflatex` or `latexmk`:

```bash
latexmk -pdf cv-llt.tex
```

