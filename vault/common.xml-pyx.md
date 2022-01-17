---
id: common.xml-pyx
title: Xml Pyx
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
# xml pyx

> Convert an XML document to PYX (ESIS - ISO 8879) format.
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Convert an XML document to PYX format:

`xml pyx {{path/to/input.xml|URI}} > {{path/to/output.pyx}}`

- Convert an XML document from stdin to PYX format:

`cat {{path/to/input.xml}} | xml pyx > {{path/to/output.pyx}}`

- Display help for the `pyx` subcommand:

`xml pyx --help`

