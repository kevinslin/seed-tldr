---
id: linux.xtrlock
title: Xtrlock
desc: ''
updated: 1615663978758
created: 1615663978758
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# xtrlock

> Lock the X display until the user supplies their password.

- Lock the display and show a padlock instead of the cursor:

`xtrlock`

- Display a blank screen as well as the padlock cursor:

`xtrlock -b`

- Fork the xtrlock process and return immediately:

`xtrlock -f`

