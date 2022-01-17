---
id: common.xml-canonic
title: Xml Canonic
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
# xml canonic

> Make XML documents canonical.
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Make an XML document canonical, preserving comments:

`xml canonic {{path/to/input.xml|URI}} > {{path/to/output.xml}}`

- Make an XML document canonical, removing comments:

`xml canonic --without-comments {{path/to/input.xml|URI}} > {{path/to/output.xml}}`

- Make XML exclusively canonical, using an XPATH from a file, preserving comments:

`xml canonic --exc-with-comments {{path/to/input.xml|URI}} {{path/to/c14n.xpath}}`

- Display help for the `canonic` subcommand:

`xml canonic --help`

