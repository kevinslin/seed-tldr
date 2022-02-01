---
id: common.asciidoctor
title: Asciidoctor
desc: ''
updated: 1642441814995
created: 1642441814995
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# asciidoctor

> A processor that converts AsciiDoc files to a publishable format.
> More information: <https://docs.asciidoctor.org>.

- Convert a specific `.adoc` file to HTML (the default output format):

`asciidoctor {{path/to/file.adoc}}`

- Convert a specific `.adoc` file to HTML and link a CSS stylesheet:

`asciidoctor -a stylesheet={{path/to/stylesheet.css}} {{path/to/file.adoc}}`

- Convert a specific `.adoc` file to embeddable HTML, removing everything except the body:

`asciidoctor --embedded {{path/to/file.adoc}}`

- Convert a specific `.adoc` file to a PDF using the `asciidoctor-pdf` library:

`asciidoctor --backend={{pdf}} --require={{asciidoctor-pdf}} {{path/to/file.adoc}}`

