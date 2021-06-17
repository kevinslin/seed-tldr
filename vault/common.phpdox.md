---
id: common.phpdox
title: Phpdox
desc: ''
updated: 1623965016143
created: 1623965016143
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# phpdox

> A PHP documentation generator.
> More information: <https://phpdox.net>.

- Display an annotated skeleton configuration XML file:

`phpdox --skel`

- Generate documentation for the current working directory:

`phpdox`

- Generate documentation using a specific configuration file:

`phpdox --file {{path/to/phpdox.xml}}`

- Only run the metadata collection process:

`phpdox --collector`

- Only run the documentation generator process:

`phpdox --generator`

