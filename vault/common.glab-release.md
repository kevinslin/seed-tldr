---
id: common.glab-release
title: Glab Release
desc: ''
updated: 1642574148922
created: 1642574148922
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# glab release

> Manage GitLab releases from the command-line.
> More information: <https://glab.readthedocs.io/en/latest/release>.

- List releases in a Gitlab repository, limited to 30 items:

`glab release list`

- Display information about a specific release:

`glab release view {{tag}}`

- Create a new release:

`glab release create {{tag}}`

- Delete a specific release:

`glab release delete {{tag}}`

- Download assets from a specific release:

`glab release download {{tag}}`

- Upload assets to a specific release:

`glab release upload {{tag}} {{path/to/file1}} {{path/to/file2}}`

