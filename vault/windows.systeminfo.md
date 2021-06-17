---
id: windows.systeminfo
title: Systeminfo
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
# systeminfo

> Display operating system configuration for a local or remote machine.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/systeminfo>.

- Display system configuration for the local machine:

`systeminfo`

- Display system configuration in a specified output format:

`systeminfo /fo {{table|list|csv}}`

- Display system configuration for a remote machine:

`systeminfo /s {{remote_name}} /u {{username}} /p {{password}}`

- Display detailed usage information:

`systeminfo /?`

