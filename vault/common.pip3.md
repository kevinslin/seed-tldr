---
id: common.pip3
title: Pip3
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
# pip3

> Python package manager.
> More information: <https://pip.pypa.io>.

- Find available packages:

`pip3 search {{package_name}}`

- Install a package:

`pip3 install {{package_name}}`

- Install a specific version of a package:

`pip3 install {{package_name}}=={{package_version}}`

- Upgrade a package:

`pip3 install --upgrade {{package_name}}`

- Uninstall a package:

`pip3 uninstall {{package_name}}`

- Save the list of installed packages to a file:

`pip3 freeze > {{requirements.txt}}`

- Install packages from a file:

`pip3 install --requirement {{requirements.txt}}`

- Show installed package info:

`pip3 show {{package_name}}`

