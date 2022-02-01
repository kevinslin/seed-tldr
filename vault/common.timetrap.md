---
id: common.timetrap
title: Timetrap
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
# timetrap

> Simple command-line time tracker written in Ruby.
> More information: <https://github.com/samg/timetrap>.

- Create a new timesheet:

`timetrap sheet {{timesheet}}`

- Check in an entry started 5 minutes ago:

`timetrap in --at "{{5 minutes ago}}" {{entry_notes}}`

- Display the current timesheet:

`timetrap display`

