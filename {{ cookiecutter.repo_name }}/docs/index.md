# {{ cookiecutter.pypi_project_name }}

<div class="badges">
    <a href="http://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}?branch=master">
        <img src="https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}.svg?branch=masterr">
    </a>
    <a href="https://pypi.python.org/pypi/{{ cookiecutter.pypi_project_name }}">
        <img src="https://pypip.in/version/{{ cookiecutter.pypi_project_name }}/badge.svg">
    </a>
</div>

## Overview

{{ cookiecutter.project_short_description }}

## Requirements

* Python (2.7, 3.3, 3.4)
* Django (1.6, 1.7)

## Installation

Install using `pip`...

```bash
$ pip install {{ cookiecutter.pypi_project_name }}
```

## Example

TODO: Write example.

## Testing

Install testing requirements.

```bash
$ pip install -r requirements-test.txt
```

Run with runtests.

```bash
$ ./runtests.py
```

You can also use the excellent [tox](http://tox.readthedocs.org/en/latest/) testing tool to run the tests against all supported versions of Python and Django. Install tox globally, and then simply run:

```bash
$ tox
```

## Documentation

To build the documentation, you'll need to install `mkdocs`.

```bash
$ pip install mkdocs
```

To preview the documentation:

```bash
$ mkdocs serve
Running at: http://127.0.0.1:8000/
```

To build the documentation:

```bash
$ mkdocs build
```
