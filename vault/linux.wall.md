---
id: linux.wall
title: Wall
desc: ''
updated: 1615663978757
created: 1615663978757
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wall

> Write a message on the terminals of users currently logged in.

- Send a message:

`echo "{{message}}" | wall`

- Send a message from a file:

`wall {{file}}`

- Send a message with timeout (default 300):

`wall -t {{seconds}} {{file}}`
