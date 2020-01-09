# `expsagetex` — Introduction and examples

`expsagetex.tex` is the main document about `expsagetex`, along with (currently)
this [answer on TeX.SE][answer]. To compile this file yourself, you need Sage.
`sagetex.sty`, shipped with Sage, must be in your `TEXINPUTS`. When these
requirements are fulfilled, you can run for instance:
```
pdflatex expsagetex.tex
sage expsagetex.sagetex.sage
pdflatex expsagetex.tex
pdflatex expsagetex.tex
```
This should work as well if you replace `pdflatex` with `lualatex` or
`xelatex`.

  [answer]: https://tex.stackexchange.com/a/521389/73317
