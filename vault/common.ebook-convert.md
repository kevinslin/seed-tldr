---
id: common.ebook-convert
title: Ebook Convert
desc: ''
updated: 1615663978707
created: 1615663978707
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ebook-convert

> Can be used to convert ebooks between common formats, e.g., pdf, epub and mobi.
> Part of the Calibre ebook library tool.
> More information: <https://manual.calibre-ebook.com/generated/en/ebook-convert.html>.

- Convert an ebook into another format:

`ebook-convert {{source}} {{destination}}`

- Convert Markdown or HTML to ebook with TOC, title and author:

`ebook-convert {{source}} {{destination}} --level1-toc="//h:h1" --level2-toc="//h:h2" --level3-toc="//h:h3" --title={{title}} --authors={{author}}`

