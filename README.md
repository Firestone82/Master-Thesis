# Master-Thesis

LaTeX source for my Master's thesis: *LLM-Assisted Code Review in Kelvin*, VŠB-TUO, 2025.

![LaTeX](https://img.shields.io/badge/LaTeX-TeX-blue)

## About

This repository contains the complete LaTeX source of my Master's thesis submitted at VŠB-TUO, Faculty of Electrical Engineering and Computer Science. The thesis documents the design and implementation of LLM-powered automated code review within [Kelvin](https://kelvin.cs.vsb.cz) — the code examination platform used at VŠB-TUO. It covers prompt engineering, integration of OpenAI-compatible models into the Kelvin evaluation pipeline, and quality evaluation against human-authored feedback.

The Kelvin platform itself is at [Firestone82/kelvin](https://github.com/Firestone82/kelvin).

## Build

Requires a full TeX Live or MiKTeX installation.

1. Compile the document:
   ```bash
   pdflatex main.tex
   biber main
   pdflatex main.tex
   pdflatex main.tex
   ```

   Or open `main.tex` in [Overleaf](https://overleaf.com) or TeXstudio for a GUI workflow.

## License

© Pavel Mikula, 2025. All rights reserved. The thesis text may not be reproduced without permission.
