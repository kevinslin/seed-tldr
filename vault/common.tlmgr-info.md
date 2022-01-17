---
id: common.tlmgr-info
title: Tlmgr Info
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
# tlmgr info

> Show information about TeX Live packages.
> More information: <https://www.tug.org/texlive/tlmgr.html>.

- List all available TeX Live packages, prefexing installed ones with `i`:

`tlmgr info`

- List all available collections:

`tlmgr info collections`

- List all available schemes:

`tlmgr info scheme`

- Show information about a specific package:

`tlmgr info {{package_name}}`

- List all files contained in a specific package:

`tlmgr info {{package_name}} --list`

- List all installed packages:

`tlmgr info --only-installed`

- Show only specific information about a package:

`tlmgr info {{package_name}} --data "{{name}},{{category}},{{installed}},{{size}},{{depends}},..."`

- Print all available packages as JSON encoded array:

`tlmgr info --json`

