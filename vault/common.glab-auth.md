---
id: common.glab-auth
title: Glab Auth
desc: ''
updated: 1644066299711
created: 1644066299711
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# glab auth

> Authenticate with a GitLab host from the command-line.
> More information: <https://glab.readthedocs.io/en/latest/auth>.

- Log in with interactive prompt:

`glab auth login`

- Log in with a token:

`glab auth login --token {{token}}`

- Check authentication status:

`glab auth status`

- Log in to a specific GitLab instance:

`glab auth login --hostname {{gitlab.example.com}}`

