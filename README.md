# Canvas File Scraper

This repo hosts a simple python script to download all available files in all courses on your Canvas page.

## Dependencies

- Python 3.11+
- [setuptools-scm](https://pypi.org/project/setuptools-scm/) >= 8.0

### pipenv

#### Installation

```shell
pipenv install .
```

#### Direct Usage

```shell
pipenv run canvas-scraper ...
```

### pipx

#### Installation

```shell
pipx install .
```

## Usage
```shell
canvas-scraper <CANVAS-API-KEY>
```

## Setup Directions

For info on how to get an API key please refer to the [Canvas Dev course](https://canvas.instructure.com/courses/785215/pages/getting-started-with-the-api).

## TODO

 - Add async option.
 - Add support for more item types.
 - Store returned JSON data from Canvas API.
