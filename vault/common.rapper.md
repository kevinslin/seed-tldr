---
id: common.rapper
title: Rapper
desc: ''
updated: 1642441815064
created: 1642441815064
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rapper

> The Raptor RDF parsing utility.
> Part of the Raptor RDF Syntax Library.
> More information: <http://librdf.org/raptor/rapper.html>.

- Convert an RDF/XML document to Turtle:

`rapper -i rdfxml -o turtle {{file}}`

- Count the number of triples in a Turtle file:

`rapper -i turtle -c {{file}}`

