---
id: common.chezmoi
title: Chezmoi
desc: ''
updated: 1615663978702
created: 1615663978702
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Chezmoi

> A multi-machine dotfile manager, written in Go.
> More information: <https://chezmoi.io>.

- Initialize chezmoi on your machine:

`chezmoi init`

- Tell chezmoi to manage a dotfile:

`chezmoi add {{path/to/file}}`

- Edit the source state of a tracked dotfile:

`chezmoi edit {{path/to/file}}`

- See changes chezmoi would make:

`chezmoi diff`

- Apply the changes:

`chezmoi -v apply`

- Set chezmoi up on another machine by downloading existing dotfiles from a Git repository:

`chezmoi init {{https://example.com/path/to/repository.git}}`

- Fetch the latest changes from a remote repository:

`chezmoi update`

