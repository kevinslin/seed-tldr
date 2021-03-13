---
id: osx.qlmanage
title: Qlmanage
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# qlmanage

> QuickLook server tool.

- Display QuickLook for one or multiple files:

`qlmanage -p {{filename}} {{filename2}}`

- Compute 300px wide PNG thumbnails of all JPEGs in the current directory and put them in a directory:

`qlmanage {{*.jpg}} -t -s {{300}} {{path/to/directory}}`

- Reset Quicklook:

`qlmanage -r`

