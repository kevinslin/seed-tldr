---
id: osx.xsltproc
title: Xsltproc
desc: ''
updated: 1644840636314
created: 1644840636314
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xsltproc

> Transform XML with XSLT to produce output (usually HTML or XML).
> More information: <http://www.xmlsoft.org/xslt/xsltproc.html>.

- Transform an XML file with a specific XSLT stylesheet:

`xsltproc --output {{output.html}} {{stylesheet.xslt}} {{xmlfile.xml}}`

- Pass a value to a parameter in the stylesheet:

`xsltproc --output {{output.html}} --stringparam "{{name}}" "{{value}}" {{stylesheet.xslt}} {{xmlfile.xml}}`

