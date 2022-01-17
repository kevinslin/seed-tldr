---
id: linux.cal
title: Cal
desc: ''
updated: 1642441815090
created: 1642441815090
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cal

> Prints calendar information, with the current day highlighted.
> More information: <https://manned.org/cal>.

- Display a calendar for the current month:

`cal`

- Display previous, current and next month:

`cal -3`

- Use Monday as the first day of the week:

`cal --monday`

- Display a calendar for a specific year (4 digits):

`cal {{year}}`

- Display a calendar for a specific month and year:

`cal {{month}} {{year}}`

