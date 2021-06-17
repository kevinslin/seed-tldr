---
id: common.nativefier
title: Nativefier
desc: ''
updated: 1623965306198
created: 1623965306198
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nativefier

> Command-line tool to create a desktop app for any web site with minimal configuration.
> More information: <https://github.com/jiahaog/nativefier>.

- Make a desktop app for a website:

`nativefier {{url}}`

- Create a desktop app with a custom name:

`nativefier --name {{name}} {{url}}`

- Use a custom icon, should be a PNG:

`nativefier --icon {{path/to/icon.png}} {{url}}`

