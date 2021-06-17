---
id: linux.uuidgen
title: Uuidgen
desc: ''
updated: 1623965016170
created: 1623965016170
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# uuidgen

> Generate unique identifiers (UUIDs).
> See also `uuid`.
> More information: <https://manned.org/uuidgen>.

- Create a random UUIDv4:

`uuidgen --random`

- Create a UUIDv1 based on the current time:

`uuidgen --time`

- Create a UUIDv5 of the name with a specified namespace prefix:

`uuidgen --sha1 --namespace {{@dns|@url|@oid|@x500}} --name {{object_name}}`

