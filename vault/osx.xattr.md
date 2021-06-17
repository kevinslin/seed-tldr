---
id: osx.xattr
title: Xattr
desc: ''
updated: 1623965306236
created: 1623965306236
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xattr

> Utility to work with extended filesystem attributes.

- List key:value extended attributes for a given file:

`xattr -l {{file}}`

- Write an attribute for a given file:

`xattr -w {{attribute_key}} {{attribute_value}} {{file}}`

- Delete an attribute from a given file:

`xattr -d {{com.apple.quarantine}} {{file}}`

- Delete all extended attributes from a given file:

`xattr -c {{file}}`

- Recursively delete an attribute in a given directory:

`xattr -rd {{attribute_key}} {{directory}}`

