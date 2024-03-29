---
id: common.pyflakes
title: Pyflakes
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

