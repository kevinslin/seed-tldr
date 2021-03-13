---
id: common.pinky
title: Pinky
desc: ''
updated: 1615663978730
created: 1615663978730
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pinky

> Print user information using the `finger` protocol.

- Display details about the current user:

`pinky`

- Display details for a specific user:

`pinky {{user}}`

- Display details in the long format:

`pinky {{user}} -l`

- Omit the user's home directory and shell in long format:

`pinky {{user}} -lb`

- Omit the user's project file in long format:

`pinky {{user}} -lh`

- Omit the column headings in short format:

`pinky {{user}} -f`

