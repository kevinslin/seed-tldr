---
id: common.csvclean
title: Csvclean
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
# csvclean

> Finds and cleans common syntax errors in CSV files.
> Included in csvkit.
> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvclean.html>.

- Clean a CSV file:

`csvclean {{bad.csv}}`

- List locations of syntax errors in a CSV file:

`csvclean -n {{bad.csv}}`

