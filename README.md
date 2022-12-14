# burden

> Originally written for my "template" cookiecutter project. 'Burden' uses the ridiculously usefull invoke library to automate
> several project maintenance and publishing tasks.

[Invoke][invoke-url] provides a clean, high level API for running shell commands and defining/organizing task functions from a tasks.py file:

## Installation

Copy the "tasks.py.jinja" file to the root of your project (remove jinja suffix)

## Usage example

Burden provides the following tasks...

```shell
inv --list
Available tasks:

  bandit                     Runs bandit against selected python files.
  build                      Creates a new sdist & wheel build using the PyPA tool.
  clean                      Removes all test, build, log and lint artifacts from the environment.
  docs                       Build documentation.
  lint                       Run all lint tasks on 'src' files only.
  lint-all                   Run all lint tasks on all files.
  lint-black (bl, black)     Runs black formatter against selected python files.
  lint-flake8 (fl, flake8)   Run flake8 against selected files.
  lint-isort (is, isort)     Run isort against selected python files.
  mypy                       Run mypy against selected python files.
  psr                        Runs semantic-release publish.
  publish                    Uploads a build to the PyPI-test and PyPI python repositories.
  pypi                       Uploads a build to the PyPI python repository.
  pypi-test                  Uploads a build to the PyPI-test python repository.
  safety                     Runs safety to check for insecure requirements.
  secure                     Runs all security tools.
  tests                      Run tests using pytest.
  update                     Updates the development environment
```

## Meta

[![](assets/linkedin.png)](https://linkedin.com/in/stephen-k-3a4644210)
[![](assets/github.png)](https://github.com/Stephen-RA-King)
[![](assets/pypi.png)](https://pypi.org/project/burden/)
[![](assets/www.png)](https://www.justpython.tech)
[![](assets/email.png)](mailto:stephen.ra.king@gmail.com)
[![](assets/cv.png)](https://www.justpython.tech/cv)

Stephen R A King : stephen.ra.king@gmail.com

Distributed under the MIT license. See [license][license-url] for more information.

[https://github.com/Stephen-RA-King/burden](https://github.com/Stephen-RA-King/burden)

Created with Cookiecutter template: [**cc_template**][cc_template-url] version 1.2.1

<!-- Markdown link & img dfn's -->

[bandit-image]: https://img.shields.io/badge/security-bandit-yellow.svg
[bandit-url]: https://github.com/PyCQA/bandit
[black-image]: https://img.shields.io/badge/code%20style-black-000000.svg
[black-url]: https://github.com/psf/black
[cc_template-url]: https://github.com/Stephen-RA-King/cc_template
[codeclimate-image]: https://api.codeclimate.com/v1/badges/7fc352185512a1dab75d/maintainability
[codeclimate-url]: https://codeclimate.com/github/Stephen-RA-King/burden/maintainability
[codecov-image]: https://codecov.io/gh/Stephen-RA-King/burden/branch/main/graph/badge.svg
[codecov-url]: https://app.codecov.io/gh/Stephen-RA-King/burden
[codefactor-image]: https://www.codefactor.io/repository/github/Stephen-RA-King/burden/badge
[codefactor-url]: https://www.codefactor.io/repository/github/Stephen-RA-King/burden
[codeql-image]: https://github.com/Stephen-RA-King/burden/actions/workflows/codeql-analysis.yml/badge.svg
[codeql-url]: https://github.com/Stephen-RA-King/burden/actions/workflows/codeql-analysis.yml
[commitizen-image]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[commitizen-url]: http://commitizen.github.io/cz-cli/
[conventional-commits-image]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg?style=flat-square
[conventional-commits-url]: https://conventionalcommits.org
[deepsource-image]: https://static.deepsource.io/deepsource-badge-light-mini.svg
[deepsource-url]: https://deepsource.io/gh/Stephen-RA-King/burden/?ref=repository-badge
[downloads-image]: https://static.pepy.tech/personalized-badge/burden?period=total&units=international_system&left_color=black&right_color=orange&left_text=Downloads
[downloads-url]: https://pepy.tech/project/burden
[format-image]: https://img.shields.io/pypi/format/burden
[invoke-url]: https://github.com/pyinvoke/invoke
[isort-image]: https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336
[isort-url]: https://github.com/pycqa/isort/
[lgtm-alerts-image]: https://img.shields.io/lgtm/alerts/g/Stephen-RA-King/burden.svg?logo=lgtm&logoWidth=18
[lgtm-alerts-url]: https://lgtm.com/projects/g/Stephen-RA-King/burden/alerts/
[lgtm-quality-image]: https://img.shields.io/lgtm/grade/python/g/Stephen-RA-King/burden.svg?logo=lgtm&logoWidth=18
[lgtm-quality-url]: https://lgtm.com/projects/g/Stephen-RA-King/burden/context:python
[license-image]: https://img.shields.io/pypi/l/burden
[license-url]: https://github.com/Stephen-RA-King/burden/blob/main/license
[mypy-image]: http://www.mypy-lang.org/static/mypy_badge.svg
[mypy-url]: http://mypy-lang.org/
[pre-commit-image]: https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white
[pre-commit-url]: https://github.com/pre-commit/pre-commit
[pre-commit.ci-image]: https://results.pre-commit.ci/badge/github/Stephen-RA-King/burden/main.svg
[pre-commit.ci-url]: https://results.pre-commit.ci/latest/github/Stephen-RA-King/burden/main
[pypi-url]: https://pypi.org/project/burden/
[pypi-image]: https://img.shields.io/pypi/v/burden.svg
[python-version-image]: https://img.shields.io/pypi/pyversions/burden
[readthedocs-image]: https://readthedocs.org/projects/burden/badge/?version=latest
[readthedocs-url]: https://burden.readthedocs.io/en/latest/?badge=latest
[requirements-status-image]: https://requires.io/github/Stephen-RA-King/burden/requirements.svg?branch=main
[requirements-status-url]: https://requires.io/github/Stephen-RA-King/burden/requirements/?branch=main
[status-image]: https://img.shields.io/pypi/status/burden.svg
[tests-image]: https://github.com/Stephen-RA-King/burden/actions/workflows/tests.yml/badge.svg
[tests-url]: https://github.com/Stephen-RA-King/burden/actions/workflows/tests.yml
[wiki]: https://github.com/Stephen-RA-King/burden/wiki
