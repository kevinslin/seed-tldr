---
id: common.csvgrep
title: Csvgrep
desc: ''
updated: 1623965016118
created: 1623965016118
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csvgrep

> Filter CSV rows with string and pattern matching.
> Included in csvkit.
> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvgrep.html>.

- Find rows that have a certain string in column 1:

`csvgrep -c {{1}} -m {{string_to_match}} {{data.csv}}`

- Find rows in which columns 3 or 4 match a certain regular expression:

`csvgrep -c {{3,4}} -r {{regular_expression}} {{data.csv}}`

- Find rows in which the "name" column does NOT include the string "John Doe":

`csvgrep -i -c {{name}} -m "{{John Doe}}" {{data.csv}}`

