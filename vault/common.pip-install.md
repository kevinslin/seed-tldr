---
id: common.pip-install
title: Pip Install
desc: ''
updated: 1615663978730
created: 1615663978730
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

`pip install -r {{requirements.txt}}`

- Install the local package in the current directory in develop (editable) mode:

`pip install -e .`

