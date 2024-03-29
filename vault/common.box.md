---
id: common.box
title: Box
desc: ''
updated: 1642441814999
created: 1642441814999
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# box

> A PHP application for building and managing Phars.
> More information: <https://github.com/box-project/box>.

- Compile a new Phar file:

`box compile`

- Compile a new Phar file using a specific config file:

`box compile -c {{path/to/config}}`

- Display information about the PHAR PHP extension:

`box info`

- Display information about a specific Phar file:

`box info {{path/to/phar_file}}`

- Validate the first found config file in the working directory:

`box validate`

- Verify the signature of a specific Phar file:

`box verify {{path/to/phar_file}}`

- Display all available commands and options:

`box help`

