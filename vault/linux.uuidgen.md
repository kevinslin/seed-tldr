---
id: linux.uuidgen
title: Uuidgen
desc: ''
updated: 1615663978757
created: 1615663978757
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# uuidgen

> Generate unique identifiers (UUIDs).

- Create a random UUID:

`uuidgen --random`

- Create a UUID based on the current time:

`uuidgen --time`

- Create a UUID based on the hash of a URL:

`uuidgen --sha1 --namespace {{@url}} --name {{object_name}}`

