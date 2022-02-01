---
id: common.glab-issue
title: Glab Issue
desc: ''
updated: 1642574148922
created: 1642574148922
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# glab issue

> Manage GitLab issues from the command-line.
> More information: <https://glab.readthedocs.io/en/latest/issue>.

- Display a specific issue:

`glab issue view {{issue_number}}`

- Create a new issue in the default web browser:

`glab issue create --web`

- List the last 10 issues with the `bug` label:

`glab issue list --per-page {{10}} --label "{{bug}}"`

- List closed issues made by a specific user:

`glab issue list --closed --author {{username}}`

- Reopen a specific issue:

`glab issue reopen {{issue_number}}`

