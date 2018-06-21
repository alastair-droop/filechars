# Tabulate 8-byte characters in a File

This script counts the number of each 8-byte character occurring in the input file.

## Usage

~~~
usage: filechars [-h] [-v] [-V {error,warning,info,debug}] [-e] [-r] [-s]
                 [-b <n>]
                 [<file>]

Tabulate single (8-byte) characters in a file

positional arguments:
  <file>                input file

optional arguments:
  -h, --help            show this help message and exit
  -v, --version         show program's version number and exit
  -V {error,warning,info,debug}, --verbose {error,warning,info,debug}
                        Set logging level (default warning)
  -e, --include-empty   list empty characters
  -r, --include-representation
                        output character representation
  -s, --sort-output     sort output character counts
  -b <n>, --block-size <n>
                        block read size
~~~
