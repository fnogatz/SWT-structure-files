# Structure files for SWT Swiss Chess Tournament files

This is a collection of files which describe the binary format of chess tournament files used by [Swiss-Chess for Windows](http://www.swiss-chess.de/).

## Supported SWT versions

Currently the following SWT version are supported:

- [7.xx](https://github.com/fnogatz/SWT-structure-files/tree/master/700)
- [8.xx](https://github.com/fnogatz/SWT-structure-files/tree/master/800)

The file format definitions for the different versions are placed into appropriate directories. For every change that is not backwards-compatible we add a new directory named as the lowest version for which this new definition file should be applied. If there is no file for a given version, the file of the next lower version should be used. In this way we only track breaking changes in the file format specification in this repository.

## FAQ

> Why don't you provide a parser instead of the structure files?

The aim of this project is to build a basis which can be used for parsers in different programming languages. Currently there is one for [node.js](https://github.com/fnogatz/node-swtparser) and another written in [PHP](https://github.com/koenige/swtparser), both are using these structure files. Feel free to write another in your favorite language!

> Why did you choose CSV to store the structure information?

CSV is a good standard to save the structure information because you can handle them in nearly every programming language very easily.
