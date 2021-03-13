---
id: common.pyflakes
title: Pyflakes
desc: ''
updated: 1615655543080
created: 1615655543080
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# pyflakes

> Checks Python source code files for errors.
> More information: <https://pypi.org/project/pyflakes>.

- Check a single Python file:

`pyflakes check {{path/to/file}}.py`

- Check Python files in a specific directory:

`pyflakes checkPath {{path/to/directory}}`

- Check Python files in a directory recursively:

`pyflakes checkRecursive {{path/to/directory}}`

- Check all Python files found in multiple directories:

`pyflakes iterSourceCode {{path/to/directory_1}} {{path/to/directory_2}}`

