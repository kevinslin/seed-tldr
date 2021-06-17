---
id: osx.date
title: Date
desc: ''
updated: 1623965016172
created: 1623965016172
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# date

> Set or display the system date.

- Display the current date using the default locale's format:

`date +"%c"`

- Display the current date in UTC and ISO 8601 format:

`date -u +"%Y-%m-%dT%H:%M:%SZ"`

- Display the current date as a Unix timestamp (seconds since the Unix epoch):

`date +%s`

- Display a specific date (represented as a Unix timestamp) using the default format:

`date -r 1473305798`

