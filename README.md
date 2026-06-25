# Non-Hermitian Photonics

This repository contains the open review source for the book
*Non-Hermitian Photonics: Maxwell Operators, Open Resonances, and Topological Light*.

The book is part of the Agent Book Commons workflow: source material stays open,
readers review the draft through issues and pull requests, and stable PDFs are
archived through GitHub Actions artifacts or releases.

## Build

The main source file is `main.tex`. To build locally with LuaLaTeX:

```bash
latexmk -lualatex -interaction=nonstopmode -halt-on-error main.tex
```

The GitHub Actions workflow in `.github/workflows/build-non-hermitian-pdf.yml`
also compiles the PDF on pushes, pull requests, and manual runs.

## Review

Use issues for page-level feedback, errata, citation problems, equation checks,
figure problems, or structural suggestions. Use pull requests for concrete source
changes to chapters, appendices, figures, bibliography entries, or macros.
