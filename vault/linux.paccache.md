---
id: linux.paccache
title: Paccache
desc: ''
updated: 1623965306227
created: 1623965306227
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# paccache

> A pacman cache cleaning utility.

- Remove all but the 3 most recent package versions from the pacman cache:

`paccache -r`

- Set the number of package versions to keep:

`paccache -rk {{num_versions}}`

- Perform a dry-run and show the number of candidate packages for deletion:

`paccache -d`

- Move candidate packages to a directory instead of deleting them:

`paccache -m {{path/to/directory}}`

