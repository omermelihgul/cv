# My CV Repository

This repository contains my CV in LaTeX format, which can be found in the PDF format [here](CV.pdf).

Feel free to download and review my CV to learn more about my qualifications and experience.

## Overview

The main XeLaTeX source file is `CV.tex`; the compiled document is `CV.pdf`.

Instructions for compiling the document (TeX &rarr;(XeLaTeX)&rarr; PDF):

- **Method 1:** Use `latexmk` for fully automated document generation:
   - `latexmk -xelatex "CV.tex"`
   (add the `-pvc` switch to automatically recompile on changes)

- **Method 2:** Use `XeLaTeX` directly:
   - `xelatex "CV.tex"`
   (run multiple times to resolve cross-references if needed)