---
id: common.gh-pr-create
title: Gh Pr Create
desc: ''
updated: 1642441815020
created: 1642441815020
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh pr create

> Manage GitHub pull requests from the command-line.
> More information: <https://cli.github.com/manual/gh_pr_create>.

- Interactively create a pull request:

`gh pr create`

- Create a pull request, determining the title and description from the commit messages of the current branch:

`gh pr create --fill`

- Create a draft pull request:

`gh pr create --draft`

- Create a pull request specifying the base branch, title, and description:

`gh pr create --base {{base_branch}} --title "{{title}}" --body "{{body}}"`

- Start opening a pull request in the browser:

`gh pr create --web`

