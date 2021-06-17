---
id: linux.ldconfig
title: Ldconfig
desc: ''
updated: 1623965016163
created: 1623965016163
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ldconfig

> Configure symlinks and cache for shared library dependencies.

- Update symlinks and rebuild the cache (usually run when a new library is installed):

`sudo ldconfig`

- Update the symlinks for a given directory:

`sudo ldconfig -n {{path/to/directory}}`

- Print the libraries in the cache and check whether a given library is present:

`ldconfig -p | grep {{library_name}}`

