---
id: common.dvc-add
title: Dvc Add
desc: ''
updated: 1642441815011
created: 1642441815011
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dvc add

> Add changed files to the index.
> More information: <https://dvc.org/doc/command-reference/add>.

- Add a single target file to the index:

`dvc add {{path/to/file}}`

- Add a target directory to the index:

`dvc add {{path/to/directory}}`

- Recursively add all the files in a given target directory:

`dvc add --recursive {{path/to/directory}}`

- Add a target file with a custom `.dvc` filename:

`dvc add --file {{custom_name.dvc}} {{path/to/file}}`

