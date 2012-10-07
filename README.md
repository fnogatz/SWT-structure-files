# Structure files for SWT Swiss Chess Tournament files

This is a collection of files which describe the binary format of chess tournament files used by [Swiss-Chess for Windows](http://www.swiss-chess.de/).

## Supported SWT versions

Currently the following SWT version are supported:

- 8.xx

## FAQ

> Why don't you provide a parser instead of the structure files?

The aim of this project is to build a basis which can be used for parsers in different programming languages. Currently there is only one in [PHP](https://github.com/fnogatz/swtparser) which uses these structure files. Feel free to write another in your favorite language!

> Why did you choose CSV to store the structure information?

CSV is a good standard to save the structure information because you can handle them in nearly every programming language very easily.

## Todo

- Import structure files for SWT files of version [7.xx](https://github.com/koenige/swtparser/tree/master/structure-v7xx).

## Licence

	Copyright (C) 2005, 2012 Gustaf Mossakowski, Falco Nogatz, Jacob Roggon

	This program is free software: you can redistribute it and/or modify
	it under the terms of the GNU Lesser General Public License as published by
	the Free Software Foundation, either version 3 of the License, or
	(at your option) any later version.
	
	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU Lesser General Public License for more details.
	
	You should have received a copy of the GNU Lesser General Public License
	along with this program. If not, see <http://www.gnu.org/licenses/>.

