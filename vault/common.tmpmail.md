---
id: common.tmpmail
title: Tmpmail
desc: ''
updated: 1642441815076
created: 1642441815076
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tmpmail

> A temporary email right from your terminal written in POSIX sh.
> More information: <https://github.com/sdushantha/tmpmail>.

- Create a temporary inbox:

`tmpmail --generate`

- List messages and their numeric ID:

`tmpmail`

- Display the most recent received email:

`tmpmail --recent`

- Open a specific message:

`tmpmail {{email_id}}`

- View email as raw text without HTML tags:

`tmpmail --text`

- Open email with a specific browser (default is w3m):

`tmpmail --browser {{browser}}`

