---
id: linux.toilet
title: Toilet
desc: ''
updated: 1623965016169
created: 1623965016169
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# toilet

> A tool to display ASCII-art fonts.
> More information: <http://caca.zoy.org/wiki/toilet>.

- Generate ASCII art for a given text:

`toilet {{input_text}}`

- Generate ASCII art using a custom font file:

`toilet {{input_text}} -f {{font_filename}}`

- Generate ASCII art using a filter:

`toilet {{input_text}} --filter {{filter_name}}`

- Show available toilet filters:

`toilet --filter list `

