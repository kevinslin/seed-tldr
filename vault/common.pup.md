---
id: common.pup
title: Pup
desc: ''
updated: 1623965306206
created: 1623965306206
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pup

> Command-line HTML parsing tool.
> More information: <https://github.com/ericchiang/pup>.

- Transform a raw HTML file into a cleaned, indented, and colored format:

`cat {{index.html}} | pup --color`

- Filter HTML by element tag name:

`cat {{index.html}} | pup '{{tag}}'`

- Filter HTML by id:

`cat {{index.html}} | pup '{{div#id}}'`

- Filter HTML by attribute value:

`cat {{index.html}} | pup '{{input[type="text"]}}'`

- Print all text from the filtered HTML elements and their children:

`cat {{index.html}} | pup '{{div}} text{}'`

- Print HTML as JSON:

`cat {{index.html}} | pup '{{div}} json{}'`

