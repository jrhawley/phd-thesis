# PhD thesis

This repository contains the LaTeX files, images, and compiled version of my PhD thesis, in the Department of Medical Biophysics at the University of Toronto.

To download the compiled PDF of the thesis, [see here](build/Hawley_James_R_202203_PhD_thesis/Hawley_James_R_202203_PhD_thesis.pdf).

## Usage

This document is compiled with [Tectonic](https://tectonic-typesetting.github.io/en-US/), which uses XeTeX.
XeTeX, bibtex, and other associated tools can be installed from [MikTeX](https://miktex.org/) or [TeX Live](https://tug.org/texlive/).

After installation, the document can be compiled by running

```shell
tectonic -X build
```

If you want to have live reloads after any change to the TeX files, run

```shell
tectonic -X watch
```
