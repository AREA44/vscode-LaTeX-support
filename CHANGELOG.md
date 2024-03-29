# LaTeX language support CHANGELOG

## Version 4.0.0: December 31th, 2021
- Updated `LaTeX` grammar from [VSCode LaTeX grammars](https://github.com/jlelong/vscode-latex-basics).
- Only support VSCode < 1.64. From 1.64, VSCode supported `LaTeX` grammar.

## Version 3.10.0: October 16th, 2021
- Updated `LaTeX` grammar from [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop).

## Version 3.9.0: August 1st, 2021
- [Highlighted `spverbatim`](https://github.com/AREA44/vscode-LaTeX-support/issues/16).
- Updated `LaTeX` and `TeX` grammars from [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop).

## Version 3.8.0: July 9th, 2021
- Fixed [rectify typo in description key of snippets](https://github.com/AREA44/vscode-LaTeX-support/pull/15), thanks to [@sabertazimi](https://github.com/sabertazimi).
- Fixed [line comment does not work in `\cite`](https://github.com/AREA44/vscode-LaTeX-support/issues/14).
- Updated `TeX` grammar from [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop).

## Version 3.7.0: June 16th, 2021
- Updated grammars from [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop).
- Fixed [snippets for align(ed) and gather(ed)](https://github.com/AREA44/vscode-LaTeX-support/issues/13).

## Version 3.6.0: March 8th, 2021
- Updated grammars from [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop).

## Version 3.5.0: December 12th, 2020
- Auto-closing pairs with `\left` and `\right`. Fixed [`\left` and `\right` cannot be matched properly](https://github.com/AREA44/vscode-LaTeX-support/issues/9).
- Removed `$` auto-closing causes bad typing behavior.
- Added GitHub template.

## Version 3.4.0: November 14th, 2020
- Updated grammars from [LaTeX Workshop](https://github.com/James-Yu/LaTeX-Workshop).

## Version 3.0.0: April 14th, 2019
- Used `LaTeX-Workshop`'s grammars.

## Version 2.1.0: October 27th, 2018
- Fixed [VerbatimOut not recognized as a verbatim environment](https://github.com/ProAdd-ons/vscode-LaTeX-support/issues/6).

## Version 2.0.0: July 10th,2018
- Cleaned and fixed bugs.
- Supported for [Folding regions](https://code.visualstudio.com/updates/v1_17#_folding-regions). The LaTeX language currently have markers defined: `%Region` and `%Endregion`.

## Version 1.0.0: September 24th, 2017
- Converted grammars from the [LaTeX TextMate bundle](https://github.com/textmate/latex.tmbundle).
