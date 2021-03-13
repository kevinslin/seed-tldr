---
id: common.cotton
title: Cotton
desc: ''
updated: 1615663978703
created: 1615663978703
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cotton

> Markdown test specification runner.
> More information: <https://github.com/chonla/cotton>.

- Use a specific base url:

`cotton -u {{base_url}} {{file}}.md`

- Disable certificate verification (insecure mode):

`cotton -u {{base_url}} -i {{file}}.md`

- Stop running when a test fails:

`cotton -u {{base_url}} -s {{file}}.md`

