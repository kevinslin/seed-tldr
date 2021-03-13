---
id: linux.lsb_release
title: Lsb_release
desc: ''
updated: 1615663978749
created: 1615663978749
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lsb_release

> Provides certain LSB (Linux Standard Base) and distribution-specific information.

- Print all available information:

`lsb_release -a`

- Print a description (usually the full name) of the operating system:

`lsb_release -d`

- Print only the operating system name (ID), suppressing the field name:

`lsb_release -i -s`

- Print the release number and codename of the distribution, suppressing the field names:

`lsb_release -rcs`

