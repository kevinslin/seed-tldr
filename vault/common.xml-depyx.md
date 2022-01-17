---
id: common.xml-depyx
title: Xml Depyx
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
# xml depyx

> Convert a PYX (ESIS - ISO 8879) document to XML format.
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Convert a PYX (ESIS - ISO 8879) document to XML format:

`xml depyx {{path/to/input.pyx|URI}} > {{path/to/output.xml}}`

- Convert a PYX document from stdin to XML format:

`cat {{path/to/input.pyx}} | xml depyx > {{path/to/output.xml}}`

- Display help for the `depyx` subcommand:

`xml depyx --help`

