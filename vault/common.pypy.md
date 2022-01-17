---
id: common.pypy
title: Pypy
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
# pypy

> Fast and compliant alternative implementation of the Python language.
> More information: <https://doc.pypy.org>.

- Start a REPL (interactive shell):

`pypy`

- Execute script in a given Python file:

`pypy {{path/to/file.py}}`

- Execute script as part of an interactive shell:

`pypy -i {{path/to/file.py}}`

- Execute a Python expression:

`pypy -c "{{expression}}"`

- Run library module as a script (terminates option list):

`pypy -m {{module}} {{arguments}}`

- Install a package using pip:

`pypy -m pip install {{package_name}}`

- Interactively debug a Python script:

`pypy -m pdb {{path/to/file.py}}`

