# Hyperfast Python Template

[![License](https://img.shields.io/github/license/entelecheia/hyperfast-python-template)](https://github.com/entelecheia/hyperfast-python-template/blob/main/LICENSE)
[![][version-image]]((https://github.com/entelecheia/hyperfast-python-template/releases))
[![Release date](https://img.shields.io/github/release-date/entelecheia/hyperfast-python-template)](https://github.com/entelecheia/hyperfast-python-template/releases)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)
[![Jupyter Book](https://jupyterbook.org/en/stable/_images/badge.svg)](https://jupyterbook.org)

A python template that helps you jump start your project

- Documentation: [https://entelecheia.github.io/hyperfast-python-template](https://entelecheia.github.io/hyperfast-python-template)
- GitHub: [https://github.com/entelecheia/hyperfast-python-template](https://github.com/entelecheia/hyperfast-python-template)
- PyPI: [https://pypi.org/project/hyperfast-python-template](https://pypi.org/project/hyperfast-python-template)

Hyperfast Python Template is a self-contained template that helps you initialize your Python project inside the template. It is hyperfast in the sense that the template itself is converted into a Python project in the blink of an eye. It is also hyperfast in the sense that it helps you jump start your project with the best practices in the Python community.

## Usage

There are three ways to use this project:

- Use [the template][template-url] to create a new repository
- Use [Copier][copier-url] to create a project to your local machine directly
- Inject [the template][template-url] into an existing project

### I. Use the template

1. Click the `Use this template` button
2. Enter a name for your repository
3. Click `Create repository from template`
4. Clone your new repository to your local machine
5. Initialize your project with `make init-project`
6. Do your work

### II. Use Copier

1. Install Copier with `pipx install copier`
2. Run `copier gh:entelecheia/hyperfast-python-template path/to/destination`
3. Initialize your project with `make init-git`
4. Do your work

### III. Inject the template

1. Install Copier with `pipx install copier`
2. From the root of your project, run `copier gh:entelecheia/hyperfast-python-template .`
3. If your project is not a git repository, initialize it with `make init-git`
4. Do your work

## Features

- [x] Automated semantic versioning with [Python Semantic Release]
- [x] Automated uploads to [PyPI] and [TestPyPI]
- [x] Code coverage with [Coverage.py]
- [x] Code formatting with [Black] and [Prettier]
- [x] Continuous integration with [GitHub Actions]
- [x] Coverage reporting with [Pytest-Cov]
- [x] Documentation with [MkDocs], [Jupyter Book], and [Read the Docs]
- [x] Import sorting with [isort]
- [x] Linting with [pre-commit] and [Flake8]
- [x] Managing project labels with [GitHub Labeler]
- [x] Managing projects with [Make]
- [x] Packaging and dependency management with [Poetry]
- [x] Rendering projects with [Copier]
- [x] Static type-checking with [mypy]
- [x] Support for [Conventional Commits]
- [x] Support for [Semantic Release]
- [x] Testing with [pytest]

- [ ] Automated dependency updates with [Dependabot]
- [ ] Automated Python syntax upgrades with [pyupgrade]
- [ ] Automated release notes with [Release Drafter]
- [ ] Check documentation examples with [xdoctest]
- [ ] Generating API documentation with [autodoc] and [napoleon]
- [ ] Runtime type-checking with [Typeguard]
- [ ] Security audit with [Bandit] and [Safety]
- [ ] Test automation with [Nox]

The template supports Python 3.7, 3.8, 3.9, and 3.10.

[bandit]: https://github.com/PyCQA/bandit
[black]: https://github.com/psf/black
[click]: https://click.palletsprojects.com/
[codecov]: https://codecov.io/
[conventional commits]: https://conventionalcommits.org
[copier]: https://copier.readthedocs.io
[coverage.py]: https://coverage.readthedocs.io/
[dependabot]: https://dependabot.com/
[flake8]: http://flake8.pycqa.org
[furo]: https://pradyunsg.me/furo/
[github actions]: https://github.com/features/actions
[github labeler]: https://github.com/marketplace/actions/github-labeler
[isort]: https://pycqa.github.io/isort/
[jupyter book]: https://jupyterbook.org
[make]: https://www.gnu.org/software/make/
[mkdocs]: https://www.mkdocs.org
[mypy]: http://mypy-lang.org/
[myst]: https://myst-parser.readthedocs.io/
[napoleon]: https://www.sphinx-doc.org/en/master/usage/extensions/napoleon.html
[nox]: https://nox.thea.codes/
[poetry]: https://python-poetry.org/
[pre-commit]: https://pre-commit.com/
[prettier]: https://prettier.io/
[pypi]: https://pypi.org/
[pytest-cov]: https://pytest-cov.readthedocs.io/
[pytest]: https://docs.pytest.org/en/latest/
[python semantic release]: https://python-semantic-release.readthedocs.io/en/latest/
[pyupgrade]: https://github.com/asottile/pyupgrade
[read the docs]: https://readthedocs.org/
[release drafter]: https://github.com/release-drafter/release-drafter
[safety]: https://github.com/pyupio/safety
[semantic release]: https://github.com/semantic-release/semantic-release
[sphinx-click]: https://sphinx-click.readthedocs.io/
[sphinx]: http://www.sphinx-doc.org/
[testpypi]: https://test.pypi.org/
[typeguard]: https://github.com/agronholm/typeguard
[xdoctest]: https://github.com/Erotemic/xdoctest

## License

This project is released under the [MIT License][license-url].

<!-- Links: -->

[repo-url]: https://github.com/entelecheia/hyperfast-python-template
[pypi-url]: https://pypi.org/project/hyperfast-python-template
[docs-url]: https://entelecheia.github.io/hyperfast-python-template
[version-image]: https://img.shields.io/github/v/release/entelecheia/hyperfast-python-template?sort=semver
[release-date-image]: https://img.shields.io/github/release-date/entelecheia/hyperfast-python-template
[release-url]: https://github.com/entelecheia/hyperfast-python-template/releases
[license-image]: https://img.shields.io/github/license/entelecheia/hyperfast-python-template
[license-url]: https://github.com/entelecheia/hyperfast-python-template/blob/main/LICENSE
[changelog-url]: https://github.com/entelecheia/hyperfast-python-template/blob/main/CHANGELOG.md

[template-url]: https://github.com/entelecheia/hyperfast-python-template
[semantic-image]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[conventional-commits-image]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white
[jupyter-book-image]: https://jupyterbook.org/en/stable/_images/badge.svg
