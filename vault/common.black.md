---
id: common.black
title: Black
desc: ''
updated: 1623965306175
created: 1623965306175
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# black

> A Python auto code formatter.
> More information: <https://github.com/psf/black>.

- Auto-format a file or entire directory:

`black {{path/to/file_or_directory}}`

- Format the code passed in as a string:

`black -c {{path/to/file_or_directory}}`

- Output a diff for each file on stdout:

`black --diff {{path/to/file_or_directory}}`

- Return the status without writing the files back:

`black --check {{path/to/file_or_directory}}`

- Auto-format a file or directory emitting exclusively error messages to stderr:

`black --quiet {{path/to/file_or_directory}}`

