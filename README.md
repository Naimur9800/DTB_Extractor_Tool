# extract-dtb

Tool to split a kernel image with appended dtbs into separated kernel and dtb files.

A Device Tree is a data structure for describing hardware. They are used in a lot of
ARM devices (e.g. Android), otherwise these would not be able to boot.

## Usage

```
$ ./extract-dtb.py --help
usage: extract-dtb.py [-h] [-o OUTPUT_DIR] [-n] [-V] filename

Example : $ ./extract-dtb.py zlmage/boot.img

optional arguments:
  -h, --help     show this help message and exit
  -o OUTPUT_DIR  Output directory
  -n             Do not extract, just output information
  -V, --version  show program's version number and exit
```

This tool can also be run directly on `boot.img` images.
