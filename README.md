# linter-mypy

[![Build Status](https://travis-ci.org/elarivie/linter-mypy.svg?branch=master)](https://travis-ci.org/elarivie/linter-mypy)
[![linter-mypy_package](https://img.shields.io/apm/dm/linter-mypy.svg?style=flat-square)][linter-mypy_package]
[![linter-mypy_BugTracker](https://img.shields.io/github/issues/elarivie/linter-mypy.svg)][linter-mypy_BugTracker]

An [Atom][atom] [Linter][linter] plugin which displays warnings related to [Python][python] optional static type as defined in [PEP 484][spec] using [mypy][mypy].

![Screen shot demo](https://github.com/elarivie/linter-mypy/raw/master/doc/ScreenShotDemo.png)

## Installation

1.  Install python package [mypy][mypy], run:

    ```ShellSession
    python3 -m pip install mypy
    ```

2.  Install package, run:

    ```ShellSession
    apm install linter-mypy
    ```

## Configuration

| Setting                             | Values           |
| ----------------------------------- | ---------------- |
| Path to the executable of `python`  | Default: python3 |
| Ignore File name Regex              | Default:         |
| Mypy ini File                       | Default:         |
| Disallow Untyped Calls              | Default: True    |
| Disallow Untyped Defs               | Default: True    |
| Check Untyped Defs                  | Default: True    |
| Disallow Subclassing Any            | Default: True    |
| Warn Incomplete Stub                | Default: True    |
| Warn Redundant Casts                | Default: True    |
| Warn No Return                      | Default: True    |
| Warn Return Any                     | Default: True    |
| Warn Unused Ignores                 | Default: True    |
| Warn Missing Imports                | Default: True    |
| Strict Optional                     | Default: True    |

[linter]: https://github.com/atom-community/linter
[install linter]: https://github.com/atom-community/linter#installation
[mypy]: https://pypi.python.org/pypi/mypy
[mypy homepage]: http://www.mypy-lang.org/
[spec]: https://www.python.org/dev/peps/pep-0484/
[atom]: https://atom.io/
[linter-mypy_repo]: https://github.com/elarivie/linter-mypy
[linter-mypy_package]: https://atom.io/packages/linter-mypy
[linter-mypy_BugTracker]: https://github.com/elarivie/linter-mypy/issues
[python]: https://www.python.org
