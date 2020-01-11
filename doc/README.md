# `expsagetex` — Introduction and examples

Along with this [answer on TeX.SE][answer], the main document about
`expsagetex` is `expsagetex.tex`. A PDF rendering of this file can be found
[here](https://github.com/frougon/expsagetex/wiki/files/expsagetex.pdf).

In case you want to compile it yourself, you need Sage. `sagetex.sty`, shipped
with Sage, must be in your `TEXINPUTS`. When these requirements are fulfilled,
you can run, for instance:

```
pdflatex expsagetex.tex
sage expsagetex.sagetex.sage
pdflatex expsagetex.tex
pdflatex expsagetex.tex
```

This should work as well if you replace `pdflatex` with `lualatex` or
`xelatex`.

  [answer]: https://tex.stackexchange.com/a/521389/73317
