---
id: common.git-mv
title: Git Mv
desc: ''
updated: 1642441815025
created: 1642441815025
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git mv

> Move or rename files and update the Git index.
> More information: <https://git-scm.com/docs/git-mv>.

- Move file inside the repo and add the movement to the next commit:

`git mv {{path/to/file}} {{new/path/to/file}}`

- Rename file and add renaming to the next commit:

`git mv {{filename}} {{new_filename}}`

- Overwrite the file in the target path if it exists:

`git mv --force {{file}} {{target}}`

