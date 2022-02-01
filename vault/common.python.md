---
id: common.python
title: Python
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
# python

> Python language interpreter.
> More information: <https://www.python.org>.

- Start a REPL (interactive shell):

`python`

- Execute a specific Python file:

`python {{path/to/file.py}}`

- Execute a specific Python file and start a REPL:

`python -i {{path/to/file.py}}`

- Execute a Python expression:

`python -c "{{expression}}"`

- Run the script of the specified library module:

`python -m {{module}} {{arguments}}`

- Install a package using `pip`:

`python -m {{pip}} install {{package_name}}`

- Interactively debug a Python script:

`python -m {{pdb}} {{path/to/file.py}}`

- Start the built-in HTTP server on port 8000 in the current directory:

`python -m {{http.server}}`

