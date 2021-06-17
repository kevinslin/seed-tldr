---
id: common.csvkit
title: Csvkit
desc: ''
updated: 1623965306178
created: 1623965306178
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csvkit

> Manipulation toolkit for CSV files.
> See the individual commands: `csvclean`, `csvcut`, `csvformat`, `csvgrep`, `csvlook`, `csvpy`, `csvsort`, `csvstat`.
> More information: <https://csvkit.readthedocs.io/en/0.9.1/cli.html>.

- Run a command on a CSV file with a custom delimiter:

`{{cmd}} -d {{delimiter}} {{filename.csv}}`

- Run a command on a CSV file with a tab as a delimiter (overrides -d):

`{{cmd}} -t {{filename.csv}}`

- Run a command on a CSV file with a custom quote character:

`{{cmd}} -q {{quote_char}} {{filename.csv}}`

- Run a command on a CSV file with no header row:

`{{cmd}} -H {{filename.csv}}`

