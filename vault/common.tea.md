---
id: common.tea
title: Tea
desc: ''
updated: 1623965306213
created: 1623965306213
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tea

> A command-line tool to interact with Gitea servers.
> More information: <https://gitea.com/gitea/tea>.

- Log into a Gitea server:

`tea login add --name "{{name}}" --url "{{url}}" --token "{{token}}"`

- Display all repositories:

`tea repos ls`

- Display a list of issues:

`tea issues ls`

- Display a list of issues for a specific repository:

`tea issues ls --repo "{{repository}}"`

- Create a new issue:

`tea issues create --title "{{title}}" --body "{{body}}"`

- Display a list of open pull requests:

`tea pulls ls`

- Open the current repository in a browser:

`tea open`

