---
id: common.nokogiri
title: Nokogiri
desc: ''
updated: 1615663978727
created: 1615663978727
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nokogiri

> An HTML, XML, SAX and Reader parser.
> More information: <https://nokogiri.org>.

- Parse the contents of a url or file:

`nokogiri {{url|path/to/file}}`

- Parse as a specific type:

`nokogiri {{url|path/to/file}} --type {{xml|html}}`

- Load a specific initialisation file before parsing:

`nokogiri {{url|path/to/file}} -C {{path/to/config_file}}`

- Parse using a specific encoding:

`nokogiri {{url|path/to/file}} --encoding {{encoding}}`

- Validate using a RELAX NG file:

`nokogiri {{url|path/to/file}} --rng {{url|path/to/file}}`

