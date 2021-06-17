---
id: common.pip
title: Pip
desc: ''
updated: 1623965306205
created: 1623965306205
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pip

> Python package manager.
> More information: <https://pip.pypa.io>.

- Install a package (see `pip install` for more install examples):

`pip install {{package_name}}`

- Upgrade a package:

`pip install -U {{package_name}}`

- Uninstall a package:

`pip uninstall {{package_name}}`

- Save installed packages to file:

`pip freeze > {{requirements.txt}}`

- Show installed package info:

`pip show {{package_name}}`

