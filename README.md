# exifstrip

A command-line tool to strip EXIF data from images.

## Requirements

- [Python 3](https://python.org)
- [pip](https://packaging.python.org/tutorials/installing-packages/)

## Installation

Install the package from [PyPI](https://pypi.org), available as [exifstrip](https://pypi.org/project/exifstrip/), using [pip](https://packaging.python.org/tutorials/installing-packages/).

```shell
pip install exifstrip
```

## Usage

```shell
usage: exifstrip [-h] [--overwrite] [images ...]

positional arguments:
  images

optional arguments:
  -h, --help   show this help message and exit
  --overwrite
```

To create a new file without EXIF data:

```shell
exifstrip path/to/img1.jpeg path/to/img2.heic
```

This will create two files, `path/to/img1.stripped.jpeg` and `path/to/img2.stripped.heic`.

To *overwrite the original file*, include the `--overwrite` flag. All files specified will be overwritten.

```shell
exifstrip path/to/img1.jpeg path/to/img2.heic --overwrite
```
