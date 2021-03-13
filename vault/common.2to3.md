---
id: common.2to3
title: 2to3
desc: ''
updated: 1615663978696
created: 1615663978696
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# 2to3

> Automated Python 2 to 3 code translation.
> More information: <https://docs.python.org/3/library/2to3.html>.

- Display changes that would be performed:

`2to3 {{path/to/file.py}}`

- Convert a Python 2 file to Python 3:

`2to3 --write {{path/to/file.py}}`

- Convert a specified Python 2 feature to Python 3:

`2to3 --write {{file.py}} --fix={{raw_input}} --fix={{print}}`

- Convert all features except _raw_input_ the specified ones to Python 3:

`2to3 --nofix={{raw_input}} --fix={{print}} example.py`

- Display the list of available transformation features:

`2to3 --list-fixes`

- Convert an entire directory:

`2to3 --output-dir={{path/to/code_python3_version}} --write-unchanged-files --nobackups {{path/to/code_python2_version}}`

