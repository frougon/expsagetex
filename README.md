# `expsagetex` — A fully expandable interface for SageTeX

## Abstract

The `\sage` and `\sagestr` macros from `sagetex.sty` do many things at once,
some of which are not “expandable” (actually, it is `\ST@sage` which does most
of the work). Since this places unnecessary limitations on what one can do
with the Sage output, `expsagetex.sty` was created to provide commands that
allow one to retrieve output from Sage in expansion-only contexts. Actually,
it was written for an update to [this TeX.SE answer][answer].

## Main requirements

`expsagetex.sty` requires `sagetex.sty` and obviously Sage. This version was
written for SageTeX 2019/01/09 v3.3. If newer versions of `sagetex.sty` change
mechanisms used by `expsagetex.sty`, the latter may need to be adapted.

## Release notes

Normally, I would have put `expsagetex.sty` in the [answer on TeX.SE][answer],
because it may be that I won't be there in the future to maintain it. However,
that wasn't possible because that would have caused the answer to exceed the
maximum number of characters allowed per answer by the
[TeX.SE][TeX.StackExchange.com questions & answers platform]. If you attempt
to contact me and don't receive a reply within two months, you can assume that
this package is not maintained anymore. In such a case, you would be welcome
to take over maintainership if you feel able, motivated and respect the
conditions given in the LICENSE file.

## Instructions and examples

Instructions and examples can be found in the doc directory as well as in the
[answer on TeX.SE][answer]. A PDF rendering of
[doc/expsagetex.tex](https://github.com/frougon/expsagetex/blob/master/doc/expsagetex.tex)
(the `expsagetex` proto-manual) can be found
[here](https://github.com/frougon/expsagetex/wiki/files/expsagetex.pdf).

## License

The `expsagetex` package is distributed under the conditions of the LaTeX
Project Public License, either version 1.3 of this license or (at your option)
any later version. See `expsagetex.sty` for the precise licensing information.
The `LICENSE` file distributed with `expsagetex` contains the complete text of
the LaTeX Project Public License version 1.3.

  [TeX.SE]: https://tex.stackexchange.com/
  [answer]: https://tex.stackexchange.com/a/521389/73317
