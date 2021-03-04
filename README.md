# Python CLI and GUI Application with Database Demo

![Python GUI Application with Database Demo](docs/screencast.gif)

**This is only for demo and reference.** Only inputs on the left most column work now!

## Installation

Install with [pip](https://pip.pypa.io/en/stable/) or download the pre-compiled executable file from [here](https://github.com/changyuheng/python-cli-and-gui-application-with-database-demo/tags).

```
pip install git+https://github.com/changyuheng/python-cli-and-gui-application-with-database-demo.git
```

## Usage

### CLI

```
cli-demo
```

### Desktop

```
desktop-demo
```

## Development

### Environment

1. [Python 3.9+](https://www.python.org/)
2. [Poetry](https://python-poetry.org/)
3. [PyCharm](https://www.jetbrains.com/pycharm/)
4. [Git](https://git-scm.com/)

### Setup

```
pip install poetry
poetry install
```

### Packaging

#### CLI app

```
poetry run pyinstaller --clean cli-demo.spec
```

#### Desktop app

```
poetry run pyinstaller --clean desktop-demo.spec
```

### Key libraries

1. [dataset](https://dataset.readthedocs.io/en/latest/)
2. [Qt for Python](https://www.qt.io/qt-for-python)

### Design concepts

1. [Object-oriented programming](https://en.wikipedia.org/wiki/Object-oriented_programming)
2. [Model–view–viewmodel (MVVM)](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel)

## References

1. [My Python Development Environment, 2020 Edition](https://jacobian.org/2019/nov/11/python-environment-2020/)

## License

[Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
