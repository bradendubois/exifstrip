# exif-strip

A command-line tool to strip EXIF data from images.

## Requirements

- [Python 3](https://python.org)
- [pip](https://packaging.python.org/tutorials/installing-packages/)

## Installation

Install the package from [PyPI](https://pypi.org), available as [exif-strip](https://pypi.org/project/exif-strip/), using [pip](https://packaging.python.org/tutorials/installing-packages/).

```shell
pip install exif-strip
```

## Usage


After installing, run:
```shell

```

To create a new file without EXIF data:

```shell
exif-strip path/to/img1.jpeg path/to/img2.heic
```

This will create two files, `path/to/img1-stripped.jpeg` and `path/to/img2.heic`.

To *overwrite the original file*, include the `--overwrite` flag. All files specified will be overwritten.

```shell
exif-strip path/to/img1.jpeg path/to/img2.heic --overwrite
```