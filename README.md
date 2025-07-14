# Beckwitt CV

This repository contains the LaTeX source for David Beckwitt's curriculum vitae.

## Structure

- `cv-llt.tex` – main document that assembles all CV sections
- `sections/` – individual TeX files for each CV section
- `bib/own-bib.bib` – bibliography entries used in publications section
- `images/` – profile photograph
- `settings.sty` – common style configuration

## Building

Run `pdflatex` (or `latexmk`) on `cv-llt.tex` to produce `cv-llt.pdf`.
