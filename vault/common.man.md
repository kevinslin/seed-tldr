---
id: common.man
title: Man
desc: ''
updated: 1615663978723
created: 1615663978723
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# man

> Format and display manual pages.

- Display the man page for a command:

`man {{command}}`

- Display the man page for a command from section 7:

`man {{command}}.{{7}}`

- Display the path searched for manpages:

`man --path`

- Display the location of a manpage rather than the manpage itself:

`man -w {{command}}`

- Search for manpages containing a search string:

`man -k "{{search_string}}"`

