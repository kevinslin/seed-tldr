---
id: common.gh-ssh-key
title: Gh Ssh Key
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
# gh ssh-key

> Manage GitHub SSH keys from the command-line.
> More information: <https://cli.github.com/manual/gh_ssh-key>.

- Display help:

`gh ssh-key`

- List SSH keys for the currently authenticated user:

`gh ssh-key list`

- Add an SSH key to the currently authenticated user's account:

`gh ssh-key add {{path/to/key.pub}}`

- Add an SSH key to the currently authenticated user's account with a specific title:

`gh ssh-key add --title {{title}} {{path/to/key.pub}}`

