---
id: common.rm
title: Rm
desc: ''
updated: 1615663978732
created: 1615663978732
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rm

> Remove files or directories.

- Remove files from arbitrary locations:

`rm {{path/to/file}} {{path/to/another/file}}`

- Recursively remove a directory and all its subdirectories:

`rm -r {{path/to/directory}}`

- Forcibly remove a directory, without prompting for confirmation or showing error messages:

`rm -rf {{path/to/directory}}`

- Interactively remove multiple files, with a prompt before every removal:

`rm -i {{file(s)}}`

- Remove files in verbose mode, printing a message for each removed file:

`rm -v {{path/to/directory/*}}`
