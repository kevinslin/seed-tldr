---
id: common.slimrb
title: Slimrb
desc: ''
updated: 1623965016149
created: 1623965016149
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# slimrb

> Convert Slim files to HTML.

- Convert a Slim file to HTML:

`slimrb {{input.slim}} {{output.html}}`

- Convert a Slim file and output to prettified HTML:

`slimrb --pretty {{input.slim}} {{output.html}}`

- Convert a Slim file to ERB:

`slimrb --erb {{input.slim}} {{output.erb}}`

