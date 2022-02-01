---
id: common.xml-validate
title: Xml Validate
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
# xml validate

> Validate XML documents.
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Validate one or more XML documents for well-formedness only:

`xml validate {{path/to/input1.xml|URI}} {{input2.xml ...}}`

- Validate one or more XML documents against a Document Type Definition (DTD):

`xml validate --dtd {{path/to/schema.dtd}} {{path/to/input1.xml|URI}} {{input2.xml ...}}`

- Validate one or more XML documents against an XML Schema Definition (XSD):

`xml validate --xsd {{path/to/schema.xsd}} {{path/to/input1.xml|URI}} {{input2.xml ...}}`

- Validate one or more XML documents against a Relax NG schema (RNG):

`xml validate --relaxng {{path/to/schema.rng}} {{path/to/input1.xml|URI}} {{input2.xml ...}}`

- Display help for the `validate` subcommand:

`xml validate --help`

