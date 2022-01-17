---
id: common.jrnl
title: Jrnl
desc: ''
updated: 1642441815037
created: 1642441815037
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jrnl

> A simple journal application for your command-line.
> More information: <http://jrnl.sh>.

- Insert a new entry with your editor:

`jrnl`

- Quickly insert a new entry:

`jrnl {{today at 3am}}: {{title}}. {{content}}`

- View the last ten entries:

`jrnl -n {{10}}`

- View everything that happened from the start of last year to the start of last march:

`jrnl -from "{{last year}}" -until {{march}}`

- Edit all entries tagged with "texas" and "history":

`jrnl {{@texas}} -and {{@history}} --edit`

