---
id: common.gh-issue-create
title: Gh Issue Create
desc: ''
updated: 1623965016125
created: 1623965016125
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh issue

> Create GitHub issues on a repository from the command-line.
> More information: <https://cli.github.com/manual/gh_issue_create>.

- Create a new issue against the current repository interactively:

`gh issue create`

- Create a new issue with the `bug` label interactively:

`gh issue create --label "{{bug}}"`

- Create a new issue interactively and assign it to the specified users:

`gh issue create --assignee {{user1,user2,...}}`

- Create a new issue with a title, body and assign it to the current user:

`gh issue create --title "{{title}}" --body "{{body}}" --assignee "{{@me}}"`

- Create a new issue interactively, reading the body text from a file:

`gh issue create --body-file {{path/to/file}}`

- Create a new issue in the default web browser:

`gh issue create --web`

- Display the help:

`gh issue create --help`

