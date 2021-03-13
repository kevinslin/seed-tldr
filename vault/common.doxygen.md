---
id: common.doxygen
title: Doxygen
desc: ''
updated: 1615663978706
created: 1615663978706
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# doxygen

> A documentation system for various programming languages.
> More information: <http://www.doxygen.nl>.

- Generate a default template configuration file `Doxyfile`:

`doxygen -g`

- Generate a template configuration file:

`doxygen -g {{path/to/config_file}}`

- Generate documentation using an existing configuration file:

`doxygen {{path/to/config_file}}`

