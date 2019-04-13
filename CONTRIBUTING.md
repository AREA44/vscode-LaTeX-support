# Contributing to LaTeX support
Welcome, and thank you for your interest in contributing to LaTeX support!

## Convert `plist` file to `json` file

If you want to convert `plist` file to `json` file, you can run `build/update-grammar.js`. This is example:

```npm
node build/update-grammar.js textmate/latex.tmbundle Syntaxes/LaTeX.plist grammars/LaTeX.json
```