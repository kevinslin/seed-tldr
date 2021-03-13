---
id: common.atom
title: Atom
desc: ''
updated: 1615663978699
created: 1615663978699
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# atom

> A cross-platform pluggable text editor.
> Plugins are managed by `apm`.
> More information: <https://atom.io/>.

- Open a file or directory:

`atom {{path/to/file_or_directory}}`

- Open a file or directory in a new window:

`atom -n {{path/to/file_or_directory}}`

- Open a file or directory in an existing window:

`atom --add {{path/to/file_or_directory}}`

- Open Atom in safe mode (does not load any additional packages):

`atom --safe`

- Prevent Atom from forking into the background, keeping Atom attached to the terminal:

`atom --foreground`

- Wait for Atom window to close before returning (useful for Git commit editor):

`atom --wait`

