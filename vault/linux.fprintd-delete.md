---
id: linux.fprintd-delete
title: Fprintd Delete
desc: ''
updated: 1642441815095
created: 1642441815095
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fprintd-delete

> Remove fingerprints from the database.
> More information: <https://manned.org/fprintd-delete>.

- Remove all fingerprints for a specific user:

`fprintd-delete {{username}}`

- Remove a specific fingerprints for a specific user:

`fprintd-delete {{username}} --finger {{left-thumb|left-index-finger|left-middle-finger|left-ring-finger|left-little-finger|right-thumb|right-index-finger|right-middle-finger|right-ring-finger|right-little-finger}}`

- Display help:

`fprintd-delete`

