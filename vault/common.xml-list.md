---
id: common.xml-list
title: Xml List
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
# xml list

> List a directory's contents (like `ls`) in XML format.
> More information: <http://xmlstar.sourceforge.net/docs.php>.

- Write the current directory's listing to an XML document:

`xml list > {{path/to/dir_list.xml}}`

- Write the specified directory's listing to an XML document:

`xml list {{path/to/directory}} > {{path/to/dir_list.xml}}`

- Display help for the `list` subcommand:

`xml list --help`

