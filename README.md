# Munge-Xournal: Programmatically manipulate Xournal and Xournal++ files

Munge-Xournal can extract page ranges and concatenate [Xournal](http://xournal.sourceforge.net/) and
[Xournal++](https://github.com/xournalpp/xournalpp) files. It can also delete layers. It is written
in Python 3 and has no further dependencies.

## Usage

```
usage: munge-xournal [-h] -o OUTPUT.XO{J,PP} [-d [LAYER [LAYER ...]]]
                     INPUT.XO{J,PP}[@m:n] [INPUT.XO{J,PP}[@m:n] ...]

positional arguments:
  INPUT.XO{J,PP}[@m:n]

optional arguments:
  -h, --help            show this help message and exit
  -o OUTPUT.XO{J,PP}, --output OUTPUT.XO{J,PP}
  -d [LAYER [LAYER ...]], --delete-layers [LAYER [LAYER ...]]
                        Layers to delete, 1-based
```

## License

Munge-Xournal is licensed to you under the MIT/X Consortium license:

Copyright (c) 2013 Andreas Klöckner and Contributors.

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.
