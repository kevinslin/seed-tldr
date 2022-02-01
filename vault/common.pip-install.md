---
id: common.pip-install
title: Pip Install
desc: ''
updated: 1642441815060
created: 1642441815060
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pip install

> Install Python packages.
> More information: <https://pip.pypa.io>.

- Install a package:

`pip install {{package_name}}`

- Install a specific version of a package:

`pip install {{package_name}}=={{package_version}}`

- Install packages listed in a file:

`pip install --requirement {{path/to/requirements.txt}}`

- Install packages from an URL or local file archive (.tar.gz | .whl):

`pip install --find-links {{url|path/to/file}}`

- Install the local package in the current directory in develop (editable) mode:

`pip install --editable {{.}}`

