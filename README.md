# Orchestrating Microbiome Analysis with Bioconductor &mdash; article <img src="figures/mia_logo.png" align="right" width="120" />

[![DOI](https://zenodo.org/badge/1035571385.svg)](https://doi.org/10.5281/zenodo.22691742)

This repository includes all the source files to used to generate article on
_Orchestrating Microbiome Analysis with Bioconductor_. This article is written
only using Quarto files, based on the
[Nature Quarto template](https://github.com/christopherkenny/nature).

Benchmark scripts were adapted from
[this separate repository](https://github.com/microbiome/benchmarking) which
contains further details on the benchmark execution and reproducibility.

## Project structure

```
.
├── _extensions/ # Quarto extensions
├── bibliography.bib # Bibliography / references
├── data/ # Data files used in the article
├── fig.eps # EPS figure used in the manuscript
├── figures/ # Additional figures
├── manuscript.qmd # Main Quarto source file (Edit this)
├── manuscript.tex # Generated LaTeX source
├── manuscript.pdf # Rendered PDF output
├── supplementary.qmd # Supplementary material source file
├── supplementary.tex # Generated LaTeX source for supplementary material
├── supplementary.pdf # Rendered PDF output for supplementary material
├── README.md # Project documentation
├── sn-apacite.bst # BibTeX style file (APA citation style)
├── sn-aps.bst # BibTeX style file (APS style)
├── sn-basic.bst # BibTeX style file (Basic Springer style)
├── sn-chicago.bst # BibTeX style file (Chicago style)
├── sn-jnl.cls # Springer LaTeX class file
├── sn-mathphys-ay.bst # BibTeX style file (Math/Physics, author-year)
├── sn-mathphys-num.bst # BibTeX style file (Math/Physics, numeric)
├── sn-nature.bst # BibTeX style file (Nature style)
└── sn-vancouver.bst # BibTeX style file (Vancouver style)
```

## Funding

<img src="figures/findingpheno_logo.png" align="right" width="160" />

This project received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 952914 ([FindingPheno](https://findingpheno.eu/)).

