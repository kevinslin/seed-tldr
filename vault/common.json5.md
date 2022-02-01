---
id: common.json5
title: Json5
desc: ''
updated: 1642441815037
created: 1642441815037
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# json5

> A command-line tool for converting JSON5 files to JSON.
> More information: <https://json5.org>.

- Convert JSON5 stdin to JSON stdout:

`echo {{input}} | json5`

- Convert a JSON5 file to JSON and output to stdout:

`json5 {{path/to/input_file.json5}}`

- Convert a JSON5 file to the specified JSON file:

`json5 {{path/to/input_file.json5}} --out-file {{path/to/output_file.json}}`

- Validate a JSON5 file:

`json5 {{path/to/input_file.json5}} --validate`

- Specify the number of spaces to indent by (or "t" for tabs):

`json5 --space {{indent_amount}}`

- View available options:

`json5 --help`

