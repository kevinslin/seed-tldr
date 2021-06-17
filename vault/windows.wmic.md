---
id: windows.wmic
title: Wmic
desc: ''
updated: 1623965306239
created: 1623965306239
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wmic

> Interactive shell for detailed information about running processes.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/wmic>.

- Fundamental grammar:

`wmic {{alias}} {{where_clause}} {{verb_clause}}`

- Show brief details about the currently running processes:

`wmic process list brief`

- Show full details about the currently running processes:

`wmic process list full`

- Access specific fields such as process name, process ID and parent process ID:

`wmic process get {{name,processid,parentprocessid}}`

- Display information about a specific process:

`wmic process where {{name="example.exe"}} list full`

- Display specific fields for a specific process:

`wmic process where processid={{pid}} get {{name,commandline}}`

- Kill a process:

`wmic process {{pid}} delete`

