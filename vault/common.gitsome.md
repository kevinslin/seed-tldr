---
id: common.gitsome
title: Gitsome
desc: ''
updated: 1615663978714
created: 1615663978714
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gitsome

> A terminal-based interface for GitHub, accessed via the `gh` command.
> It also provides menu-style autocomplete suggestions for `git` commands.
> More information: <https://github.com/donnemartin/gitsome>.

- Enter the gitsome shell (optional), to enable autocompletion and interactive help for Git (and gh) commands:

`gitsome`

- Setup GitHub integration with the current account:

`gh configure`

- List notifications for the current account (as would be seen in <https://github.com/notifications>):

`gh notifications`

- List the current account's starred repos, filtered by a given search string:

`gh starred "{{python 3}}"`

- View the recent activity feed of a given GitHub repository:

`gh feed {{tldr-pages/tldr}}`

- View the recent activity feed for a given GitHub user, using the default pager (e.g. `less`):

`gh feed {{torvalds}} -p`

