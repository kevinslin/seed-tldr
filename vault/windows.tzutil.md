---
id: windows.tzutil
title: Tzutil
desc: ''
updated: 1615663978764
created: 1615663978764
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tzutil

> A tool for displaying or configuring the system time zone.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/tzutil>.

- Get the current time zone:

`tzutil /g`

- Display a list of available time zones:

`tzutil /l`

- Set the system time zone to the specific value:

`tzutil /s {{timezone_id}}`

