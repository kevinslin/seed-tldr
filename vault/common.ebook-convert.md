---
id: common.ebook-convert
title: Ebook Convert
desc: ''
updated: 1623965306182
created: 1623965306182
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ebook-convert

> Can be used to convert e-books between common formats, e.g., pdf, epub and mobi.
> Part of the Calibre e-book library tool.
> More information: <https://manual.calibre-ebook.com/generated/en/ebook-convert.html>.

- Convert an e-book into another format:

`ebook-convert {{source}} {{destination}}`

- Convert Markdown or HTML to e-book with TOC, title and author:

`ebook-convert {{source}} {{destination}} --level1-toc="//h:h1" --level2-toc="//h:h2" --level3-toc="//h:h3" --title={{title}} --authors={{author}}`

