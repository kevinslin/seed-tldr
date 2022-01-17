---
id: osx.dot_clean
title: Dot_clean
desc: ''
updated: 1642441815120
created: 1642441815120
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dot_clean

> Merge .\_\* files with corresponding native files.
> More information: <https://ss64.com/osx/dot_clean.html>.

- Merge all `._*` files recursively:

`dot_clean {{path/to/directory}}`

- Don't recursively merge all `._*` in a directory (flat merge):

`dot_clean -f {{path/to/directory}}`

- Merge and delete all `._*` files:

`dot_clean -m {{path/to/directory}}`

- Only delete `._*` files if there's a matching native file:

`dot_clean -n {{path/to/directory}}`

- Follow symlinks:

`dot_clean -s {{path/to/directory}}`

- Print verbose output:

`dot_clean -v {{path/to/directory}}`

