---
id: common.pip-uninstall
title: Pip Uninstall
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
# pip uninstall

> Uninstall Python packages.
> More information: <https://pip.pypa.io>.

- Uninstall a package:

`pip uninstall {{package_name}}`

- Uninstall packages listed in a specific file:

`pip uninstall --requirement {{path/to/requirements.txt}}`

- Uninstall package without asking for confirmation:

`pip uninstall --yes {{package_name}}`

