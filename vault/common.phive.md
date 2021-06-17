---
id: common.phive
title: Phive
desc: ''
updated: 1623965016142
created: 1623965016142
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# phive

> The Phar Installation and Verification Environment for secure PHP application deployment.
> More information: <https://phar.io>.

- Display a list of available aliased Phars:

`phive list`

- Install a specified Phar to the local directory:

`phive install {{alias|url}}`

- Install a specified Phar globally:

`phive install {{alias|url}} --global`

- Install a specified Phar to a target directory:

`phive install {{alias|url}} --target {{path/to/directory}}`

- Update all Phar files to the latest version:

`phive update`

- Remove a specified Phar file:

`phive remove {{alias|url}}`

- Remove unused Phar files:

`phive purge`

- List all available commands:

`phive help`

