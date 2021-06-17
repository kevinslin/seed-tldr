---
id: linux.mimetype
title: Mimetype
desc: ''
updated: 1623965016164
created: 1623965016164
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mimetype

> Automatically determine the MIME type of a file.

- Print the MIME type of a given file:

`mimetype {{path/to/file}}`

- Display only the MIME type, and not the filename:

`mimetype --brief {{path/to/file}}`

- Display a description of the MIME type:

`mimetype --describe {{path/to/file}}`

- Determine the MIME type of stdin (does not check a filename):

`{{some_command}} | mimetype --stdin`

- Display debug information about how the MIME type was determined:

`mimetype --debug {{path/to/file}}`

- Display all the possible MIME types of a given file in confidence order:

`mimetype --all {{path/to/file}}`

- Explicitly specify the 2-letter language code of the output:

`mimetype --language {{path/to/file}}`

