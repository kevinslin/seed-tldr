---
id: linux.lastb
title: Lastb
desc: ''
updated: 1642441815101
created: 1642441815101
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lastb

> Show a listing of last logged in users.
> More information: <https://manned.org/lastb>.

- Show a list of all last logged in users:

`sudo lastb`

- Show a list of all last logged in users since a given time:

`sudo lastb --since {{YYYY-MM-DD}}`

- Show a list of all last logged in users until a given time:

`sudo lastb --until {{YYYY-MM-DD}}`

- Show a list of all logged in users at a specific time:

`sudo lastb --present {{hh:mm}}`

- Show a list of all last logged in users and translate the IP into a hostname:

`sudo lastb --dns`

