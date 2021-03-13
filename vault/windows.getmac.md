---
id: windows.getmac
title: Getmac
desc: ''
updated: 1615663978763
created: 1615663978763
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# getmac

> Display the MAC addresses of a system.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/getmac>.

- Display the MAC addresses for the current system:

`getmac`

- Display the details in a specific format:

`getmac /fo {{table|list|csv}}`

- Exclude the header in the output list:

`getmac /nh`

- Display the MAC addresses for a remote machine:

`getmac /s {{hostname}} /u {{username}} /p {{password}}`

- Display the MAC addresses with verbose information:

`getmac /v`

- Display detailed usage information:

`getmac /?`

