---
id: osx.caffeinate
title: Caffeinate
desc: ''
updated: 1623965306233
created: 1623965306233
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# caffeinate

> Prevent mac from sleeping.

- Prevent from sleeping for 1 hour (3600 seconds):

`caffeinate -u -t {{3600}}`

- Prevent from sleeping until a command completes:

`caffeinate -s {{command}}`

- Prevent from sleeping until you type Ctrl-C:

`caffeinate -i`

