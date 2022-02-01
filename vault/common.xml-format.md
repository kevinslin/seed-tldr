---
id: common.xml-format
title: Xml Format
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
# xml format

> Format an XML document.
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Format an XML document, indenting with tabs:

`xml format --indent-tab {{path/to/input.xml|URI}} > {{path/to/output.xml}}`

- Format an HTML document, indenting with 4 spaces:

`xml format --html --indent-spaces {{4}} {{path/to/input.html|URI}} > {{path/to/output.html}}`

- Recover parsable parts of a malformed XML document, without indenting:

`xml format --recover --noindent {{path/to/malformed.xml|URI}} > {{path/to/recovered.xml}}`

- Format an XML document from stdin, removing the `DOCTYPE` declaration:

`cat {{path\to\input.xml}} | xml format --dropdtd > {{path/to/output.xml}}`

- Format an XML document, omitting the XML declaration:

`xml format --omit-decl {{path\to\input.xml|URI}} > {{path/to/output.xml}}`

- Display help for the `format` subcommand:

`xml format --help`

