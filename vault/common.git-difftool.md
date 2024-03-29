---
id: common.git-difftool
title: Git Difftool
desc: ''
updated: 1642441815023
created: 1642441815023
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git difftool

> Show file changes using external diff tools. Accepts the same options and arguments as `git diff`.
> See also: `git diff`.
> More information: <https://git-scm.com/docs/git-difftool>.

- List available diff tools:

`git difftool --tool-help`

- Set the default diff tool to meld:

`git config --global diff.tool "{{meld}}"`

- Use the default diff tool to show staged changes:

`git difftool --staged`

- Use a specific tool (opendiff) to show changes since a given commit:

`git difftool --tool={{opendiff}} {{commit}}`

