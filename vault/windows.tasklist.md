---
id: windows.tasklist
title: Tasklist
desc: ''
updated: 1615663978764
created: 1615663978764
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tasklist

> Display a list of currently running processes on a local or remote machine.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/tasklist>.

- Display currently running processes:

`tasklist`

- Display running processes in a specified output format:

`tasklist /fo {{table|list|csv}}`

- Display running processes using the specified `.exe` or `.dll` file name:

`tasklist /m {{module_pattern}}`

- Display processes running on a remote machine:

`tasklist /s {{remote_name}} /u {{username}} /p {{password}}`

- Display services using each process:

`tasklist /svc`

