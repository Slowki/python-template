# Python Project Template

![CI](https://github.com/Slowki/python-template/workflows/CI/badge.svg?branch=master)

## Dependencies

Dependencies are managed via [`poetry`](https://python-poetry.org/).

## Unit Tests

Unit tests are run via `pytest`.

```bash
pytest
```

## Git Hooks

The [`git` hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks) are managed via [`pre-commit`](https://pre-commit.com/).

### Installing the Hooks

```bash
pre-commit install --install-hooks
```

## Building Documentation

Documentation is built with [`pdoc3`](https://pdoc3.github.io/pdoc/).

```bash
pdoc3 --html -o docs template
```
