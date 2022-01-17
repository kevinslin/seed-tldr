---
id: common.tlmgr-install
title: Tlmgr Install
desc: ''
updated: 1642441815076
created: 1642441815076
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tlmgr install

> Install TeX Live packages.
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- Install a package and its dependencies:

`sudo tlmgr install {{package}}`

- Reinstall a package:

`sudo tlmgr install --reinstall {{package}}`

- Simulate installing a package without making any changes:

`tlmgr install --dry-run {{package}}`

- Install a package without its dependencies:

`sudo tlmgr install --no-depends {{package}}`

- Install a package from a specific file:

`sudo tlmgr install --file {{path/to/package}}`

