# cookiecutter-django-rest-framework

A cookiecutter template for creating reusable Django REST Framework packages quickly.

## Features

- Travis CI configuration
- Tox configuration
- Sane setup.py for easy PyPI registration/distribution
- BSD licensed by default

## Usage

```bash
$ pip install cookiecutter
$ cookiecutter gh:jpadilla/cookiecutter-django-rest-framework
```

You'll be prompted for some questions, answer them, then it will create a cookiecutter-django-rest-framework with your new package.

### Example

Warning: After this point, change 'José Padilla', 'jpadilla', etc to your own information.

```bash
full_name (default is "Your full name here")? José Padilla
email (default is "you@example.com")? hello@jpadilla.com
github_username (default is "yourname")? jpadilla
pypi_project_name (default is "dj-package")? drf-things
repo_name (default is "dj-package")? drf-things
app_name (default is "djpackage")? drfthings
project_short_description (default is "Your project description goes here")?
year (default is "2014")?
version (default is "0.1.0")?
```

Enter the project and take a look around:

```bash
$ cd drf-things/
$ ls
```

Create a GitHub repo and push it there:

```bash
$ git init
$ git add .
$ git commit -m "first commit"
$ git remote add origin git@github.com:jpadilla/drf-things.git
$ git push -u origin master
```

## Register on PyPI

```bash
$ python setup.py register
```

## New release on PyPI

```bash
$ python setup.py publish
You probably want to also tag the version now:
      git tag -a 0.1.0 -m 'version 0.1.0'
      git push --tags
```
