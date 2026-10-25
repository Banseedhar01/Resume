# Resume

LaTeX resume sources and compiled PDF versions.

| Version | Source | PDF |
| --- | --- | --- |
| Two-page resume | [LaTeX](resume_2page_v2.tex) | [PDF](resume_2page_v2.pdf) |
| One-page resume | [LaTeX](resume_1page.tex) | [PDF](resume_1page.pdf) |

## Build

With a LaTeX distribution and `latexmk` installed:

```sh
latexmk -pdf resume_2page_v2.tex
latexmk -pdf resume_1page.tex
```

Temporary LaTeX build files are excluded from version control.
