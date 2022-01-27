# Python library template

A template repository for a modern Python library

[![GitHub Actions Status](https://github.com/MycoBean/template-robot/workflows/CI/CD/badge.svg)](https://github.com/MycoBean/template-robot/actions)
[![Code Coverage](https://codecov.io/gh/MycoBean/template-robot/graph/badge.svg?branch=master)](https://codecov.io/gh/MycoBean/template-robot?branch=master)
[![Language grade: Python](https://img.shields.io/lgtm/grade/python/g/MycoBean/template-robot.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/MycoBean/template-robot/latest/files/)
[![CodeFactor](https://www.codefactor.io/repository/github/MycoBean/template-robot/badge)](https://www.codefactor.io/repository/github/mycobean/template-robot)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

[![Docs](https://img.shields.io/badge/docs-master-blue.svg)](https://mycobean.github.io/template-robot)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MycoBean/template-robot/master)

<!-- Here libname should be replaced with your library's name on PyPI  -->
[![PyPI version](https://badge.fury.io/py/libname.svg)](https://badge.fury.io/py/libname)
[![Supported Python versions](https://img.shields.io/pypi/pyversions/libname.svg)](https://pypi.org/project/libname/)

## Controlling the version number with bumpversion

When you want to increment the version number for a new release use [`bumpversion`](https://github.com/peritus/bumpversion) to do it correctly across the whole library.
For example, to increment to a new patch release you would simply run

```
bumpversion patch
```

which given the [`.bumpversion.cfg`](https://github.com/matthewfeickert/Python-library-template/blob/master/.bumpversion.cfg) makes a new commit that increments the release version by one patch release.
