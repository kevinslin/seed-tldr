---
id: common.git-check-ignore
title: Git Check Ignore
desc: ''
updated: 1642441815022
created: 1642441815022
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git check-ignore

> Analyse and debug Git ignore / exclude (".gitignore") files.
> More information: <https://git-scm.com/docs/git-check-ignore>.

- Check whether a file or directory is ignored:

`git check-ignore {{path/to/file_or_directory}}`

- Check whether multiple files or directories are ignored:

`git check-ignore {{path/to/file}} {{path/to/directory}}`

- Use pathnames, one per line, from stdin:

`git check-ignore --stdin < {{path/to/file_list}}`

- Do not check the index (used to debug why paths were tracked and not ignored):

`git check-ignore --no-index {{path/to/files_or_directories}}`

- Include details about the matching pattern for each path:

`git check-ignore --verbose {{path/to/files_or_directories}}`

