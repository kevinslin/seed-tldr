---
id: common.doctum
title: Doctum
desc: ''
updated: 1623965016121
created: 1623965016121
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# doctum

> A PHP API documentation generator.
> More information: <https://github.com/code-lts/doctum>.

- Parse a project:

`doctum parse`

- Render a project:

`doctum render`

- Parse then render a project:

`doctum update`

- Parse and render only a specific version of a project:

`doctum update --only-version={{version}}`

- Parse and render a project using a specific configuration:

`doctum update {{path/to/config.php}}`

