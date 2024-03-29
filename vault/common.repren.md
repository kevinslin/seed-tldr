---
id: common.repren
title: Repren
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# repren

> Multi-pattern string replacement and file renaming tool.
> More information: <https://github.com/jlevy/repren>.

- Do a dry-run renaming a directory of PNGs with a literal string replacement:

`repren --dry-run --rename --literal --from '{{find_string}}' --to '{{replacement_string}}' {{*.png}}`

- Do a dry-run renaming a directory of JPEGs with a regular expression:

`repren --rename --dry-run --from '{{regular_expression}}' --to '{{replacement_string}}' {{*.jpg}} {{*.jpeg}}`

- Do a find-and-replace on the contents of a directory of CSV files:

`repren --from '{{([0-9]+) example_string}}' --to '{{replacement_string \1}}' {{*.csv}}`

- Do both a find-and-replace and a rename operation at the same time, using a pattern file:

`repren --patterns {{path/to/patfile.ext}} --full {{*.txt}}`

- Do a case-insensitive rename:

`repren --rename --insensitive --patterns {{path/to/patfile.ext}} *`

