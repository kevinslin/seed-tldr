---
id: common.skicka
title: Skicka
desc: ''
updated: 1623965306210
created: 1623965306210
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# skicka

> Manage your Google Drive.
> More information: <https://github.com/google/skicka>.

- Upload a file/folder to Google Drive:

`skicka upload {{path/to/local}} {{path/to/remote}}`

- Download a file/folder from Google Drive:

`skicka download {{path/to/remote}} {{path/to/local}}`

- List files:

`skicka ls {{path/to/folder}}`

- Show amount of space used by children folders:

`skicka du {{path/to/parent/folder}}`

- Create a folder:

`skicka mkdir {{path/to/folder}}`

- Delete a file:

`skicka rm {{path/to/file}}`

