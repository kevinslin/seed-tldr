---
id: common.xml-elements
title: Xml Elements
desc: ''
updated: 1642441815084
created: 1642441815084
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xml elements

> Extract elements and display the structure of an XML document.
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Extract elements from an XML document (producing XPATH expressions):

`xml elements {{path/to/input.xml|URI}} > {{path/to/elements.xpath}}`

- Extract elements and their attributes from an XML document:

`xml elements -a {{path/to/input.xml|URI}} > {{path/to/elements.xpath}}`

- Extract elements and their attributes and values from an XML document:

`xml elements -v {{path/to/input.xml|URI}} > {{path/to/elements.xpath}}`

- Print sorted unique elements from an XML document to see its structure:

`xml elements -u {{path/to/input.xml|URI}}`

- Print sorted unique elements from an XML document up to a depth of 3:

`xml elements -d{{3}} {{path/to/input.xml|URI}}`

- Display help for the `elements` subcommand:

`xml elements --help`

