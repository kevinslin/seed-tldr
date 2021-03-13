---
id: common.xmllint
title: Xmllint
desc: ''
updated: 1615663978740
created: 1615663978740
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xmllint

> XML parser and linter that supports XPath, a syntax for navigating XML trees.

- Return all nodes (tags) named "foo":

`xmllint --xpath "//{{foo}}" {{source_file.xml}}`

- Return the contents of the first node named "foo" as a string:

`xmllint --xpath "string(//{{foo}})" {{source_file.xml}}`

- Return the href attribute of the second anchor element in an html file:

`xmllint --html --xpath "string(//a[2]/@href)" webpage.xhtml`

- Return human-readable (indented) XML from file:

`xmllint --format {{source_file.xml}}`

- Check that a XML file meets the requirements of its DOCTYPE declaration:

`xmllint --valid {{source_file.xml}}`

- Validate XML against DTD schema hosted online:

`xmllint --dtdvalid {{URL}} {{source_file.xml}}`

