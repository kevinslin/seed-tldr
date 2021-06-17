---
id: osx.cal
title: Cal
desc: ''
updated: 1623965306233
created: 1623965306233
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cal

> Prints calendar information.

- Display a calendar for the current month:

`cal`

- Display previous, current and next month:

`cal -3`

- Display a calendar for a specific month (1-12 or name):

`cal -m {{month}}`

- Display a calendar for the current year:

`cal -y`

- Display a calendar for a specific year (4 digits):

`cal {{year}}`

- Display a calendar for a specific month and year:

`cal {{month}} {{year}}`

- Display date of Easter (Western Christian churches) in a given year:

`ncal -e {{year}}`

