---
id: osx.opensnoop
title: Opensnoop
desc: ''
updated: 1644840636310
created: 1644840636310
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# opensnoop

> Tool that tracks file opens on your system.
> More information: <https://ss64.com/osx/opensnoop.html>.

- Print all file opens as they occur:

`sudo opensnoop`

- Track all file opens by a process by name:

`sudo opensnoop -n "{{process_name}}"`

- Track all file opens by a process by PID:

`sudo opensnoop -p {{PID}}`

- Track which processes open a specified file:

`sudo opensnoop -f {{path/to/file}}`

