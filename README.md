#language-root
Grammar package for [Atom](http://atom.io) with language support for [CERN ROOT](http://root.cern.ch) scientific framework based on C++.

This grammar includes standard (core) [C++ language](https://atom.io/packages/language-c) and injects additional rules based on [ROOT coding & naming conventions](https://root.cern.ch/coding-conventions).

## Using the grammar
Since this package utilizes injections to extend  C++ language, it needs to be **active** (selected via Grammar Selector) in order to highlight the code segments properly.

In addition to automatic search of files with `.cxx`,`.cpp`,`.h`,`.C`  extensions, it also checks if the file starts with following line `// @(#)root`.
