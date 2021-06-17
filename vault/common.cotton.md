---
id: common.cotton
title: Cotton
desc: ''
updated: 1623965016117
created: 1623965016117
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cotton

> Markdown test specification runner.
> More information: <https://github.com/chonla/cotton>.

- Use a specific base URL:

`cotton -u {{base_url}} {{file}}.md`

- Disable certificate verification (insecure mode):

`cotton -u {{base_url}} -i {{file}}.md`

- Stop running when a test fails:

`cotton -u {{base_url}} -s {{file}}.md`

