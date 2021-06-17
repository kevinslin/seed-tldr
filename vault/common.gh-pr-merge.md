---
id: common.gh-pr-merge
title: Gh Pr Merge
desc: ''
updated: 1623965306185
created: 1623965306185
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh pr merge

> Merge GitHub pull requests.
> More information: <https://cli.github.com/manual/gh_pr_merge>.

- Merge the pull request associated with the current branch interactively:

`gh pr merge`

- Merge the specified pull request, interactively:

`gh pr merge {{pr_number}}`

- Merge the pull request, removing the branch on both the local and the remote:

`gh pr merge --delete-branch`

- Merge the current pull request with the specified merge strategy:

`gh pr merge --{{merge|squash|rebase}}`

- Squash the current pull request into one commit with the message body and merge:

`gh pr merge --squash --body="{{commit_message_body}}"`

- Display help:

`gh pr merge --help`

