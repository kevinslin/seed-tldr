---
id: common.cmark
title: Cmark
desc: ''
updated: 1615663978703
created: 1615663978703
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cmark

> Converts CommonMark Markdown formatted text to other formats.
> More information: <https://github.com/commonmark/cmark>.

- Render a Commonmark Markdown file to HTML:

`cmark --to html {{filename.md}}`

- Convert data from standard input to latex:

`cmark --to latex`

- Convert straight quotes to smart quotes:

`cmark --smart --to html {{filename.md}}`

- Validate utf8 characters:

`cmark --validate-utf8 {{filename.md}}`

