---
id: osx.tree
title: Tree
desc: ''
updated: 1623965306236
created: 1623965306236
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tree

> Show the contents of the current directory as a tree.
> More information: <http://mama.indstate.edu/users/ice/tree/>.

- Print files and directories up to 'num' levels of depth (where 1 means the current directory):

`tree -L {{num}}`

- Print directories only:

`tree -d`

- Print hidden files too with colorization on:

`tree -a -C`

- Print the tree without indentation lines, showing the full path instead (use `-N` to not escape whitespace and special characters):

`tree -i -f`

- Print the size of each node next to it, in human-readable format, with directories displaying their cumulative size (as in the `du` command):

`tree -s -h --du`

- Print files within the tree hierarchy, using a wildcard (glob) pattern, and pruning out directories that don't contain matching files:

`tree -P '{{*.txt}}' --prune`

- Print directories within the tree hierarchy, using the wildcard (glob) pattern, and pruning out directories that aren't ancestors of the wanted one:

`tree -P {{directory_name}} --matchdirs --prune`

- Print the tree ignoring the given directories:

`tree -I '{{directory_name1|directory_name2}}'`

