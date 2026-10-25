# Resume

LaTeX resume sources and compiled PDF versions.

| Version | Source | PDF |
| --- | --- | --- |
| Two-page resume | [LaTeX](resume_2page_v2.tex) | [PDF](resume_2page_v2.pdf) |
| D. E. Shaw resume | [LaTeX](resume_deshaw.tex) | [PDF](resume_deshaw.pdf) |

## Build

With a LaTeX distribution and `latexmk` installed:

```sh
latexmk -pdf resume_2page_v2.tex
latexmk -pdf resume_deshaw.tex
```

Temporary LaTeX build files are excluded from version control.
