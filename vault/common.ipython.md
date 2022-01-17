---
id: common.ipython
title: Ipython
desc: ''
updated: 1642441815036
created: 1642441815036
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# IPython

> A Python shell with automatic history, dynamic object introspection, easier configuration, command completion, access to the system shell and more.
> More information: <https://ipython.readthedocs.io>.

- Start a REPL (interactive shell):

`ipython`

- Enter an interactive IPython session after running a Python script:

`ipython -i {{script.py}}`

- Create default IPython profile:

`ipython profile create`

- Print the path to the directory for the default IPython profile:

`ipython locate profile`

- Clear the IPython history database, deleting all entries:

`ipython history clear`

