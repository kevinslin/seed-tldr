---
id: osx.xsltproc
title: Xsltproc
desc: ''
updated: 1623965016175
created: 1623965016175
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xsltproc

> Transform XML with XSLT to produce output (usually HTML or XML).

- Transform an XML file with a specific XSLT stylesheet:

`xsltproc --output {{output.html}} {{stylesheet.xslt}} {{xmlfile.xml}}`

- Pass a value to a parameter in the stylesheet:

`xsltproc --output {{output.html}} --stringparam {{name}} {{value}} {{stylesheet.xslt}} {{xmlfile.xml}}`

