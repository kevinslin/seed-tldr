---
id: common.git-reauthor
title: Git Reauthor
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
# git reauthor

> Change details about an author identity. Since this command rewrites the Git history, `--force` will be needed when pushing next time.
> Part of `git-extras`.
> More information: <https://github.com/tj/git-extras/blob/master/Commands.md#git-reauthor>.

- Change an author's email and name across the whole Git repository:

`git reauthor --old-email {{old@example.com}} --correct-email {{new@example.com}} --correct-name "{{name}}"`

- Change the email and name to the ones defined in the Git config:

`git reauthor --old-email {{old@example.com}} --use-config`

- Change the email and name of all commits, regardless of their original author:

`git reauthor --all --correct-email {{name@example.com}} --correct-name {{name}}`

