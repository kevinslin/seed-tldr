---
id: common.pylint
title: Pylint
desc: ''
updated: 1642441815063
created: 1642441815063
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pylint

> A Python code linter.
> More information: <https://pylint.pycqa.org/en/latest/>.

- Show lint errors in a file:

`pylint {{path/to/file.py}}`

- Lint a file and use a configuration file (usually named `pylintrc`):

`pylint --rcfile {{path/to/pylintrc}} {{path/to/file.py}}`

- Lint a file and disable a specific error code:

`pylint --disable {{C,W,no-error,design}} {{path/to/file}}`

