---
id: common.gh-issue
title: Gh Issue
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
# gh issue

> Manage GitHub issues from the command-line.
> More information: <https://cli.github.com/manual/gh_issue>.

- Print out the issue:

`gh issue view {{issue_number}}`

- Create a new issue in the web browser:

`gh issue create --web`

- List the last 10 issues with the `bug` label:

`gh issue list --limit {{10}} --label "{{bug}}"`

- List closed issues made by a specific user:

`gh issue list --state closed --author {{username}}`

- Display the status of issues relevant to the user, in a specific repository:

`gh issue status --repo {{owner}}/{{repository}}`

- Reopen an issue:

`gh issue reopen {{issue_number}}`

