---
id: linux.e4defrag
title: E4defrag
desc: ''
updated: 1642441815093
created: 1642441815093
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# e4defrag

> Defragment an ext4 filesystem.
> More information: <https://manned.org/e4defrag>.

- Defragment the filesystem:

`e4defrag {{/dev/sdXN}}`

- See how fragmented a filesystem is:

`e4defrag -c {{/dev/sdXN}}`

- Print errors and the fragmentation count before and after each file:

`e4defrag -v {{/dev/sdXN}}`

