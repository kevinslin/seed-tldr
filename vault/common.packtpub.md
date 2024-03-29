---
id: common.packtpub
title: Packtpub
desc: ''
updated: 1642441815055
created: 1642441815055
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# packtpub

> Download freely offered books from packtpub.com.
> More information: <https://github.com/vladimyr/packtpub-cli>.

- Download the daily offer book into the current directory with the specified book format (defaults to `pdf`):

`packtpub download --type {{pdf|ebup|mobi}}`

- Download the daily offer book into the specified directory:

`packtpub download --dir {{path/to/directory}}`

- Start an interactive login to packtpub.com:

`packtpub login`

- Log out from packtpub.com:

`packtpub logout`

- Display the daily offer:

`packtpub view-offer`

- Open the daily offer in the default web browser:

`packtpub view-offer`

- Display the currently logged-in user:

`packtpub whoami`

