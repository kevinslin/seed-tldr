---
id: common.csvpy
title: Csvpy
desc: ''
updated: 1642441815005
created: 1642441815005
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csvpy

> Loads a CSV file into a Python shell.
> Included in csvkit.
> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvpy.html>.

- Load a CSV file into a `CSVKitReader` object:

`csvpy {{data.csv}}`

- Load a CSV file into a `CSVKitDictReader` object:

`csvpy --dict {{data.csv}}`

