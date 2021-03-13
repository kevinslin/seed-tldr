---
id: common.pip3
title: Pip3
desc: ''
updated: 1615655543079
created: 1615655543079
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

`pip3 install --requirements {{requirements.txt}}`

- Show installed package info:

`pip3 show {{package_name}}`

