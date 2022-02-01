---
id: osx.scutil
title: Scutil
desc: ''
updated: 1642441815122
created: 1642441815122
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# scutil

> Manage system configuration parameters.
> Necessitates to be root when setting configuration.
> More information: <https://ss64.com/osx/scutil.html>.

- Display DNS Configuration:

`scutil --dns`

- Display proxy configuration:

`scutil --proxy`

- Get computer name:

`scutil --get ComputerName`

- Set computer name:

`sudo scutil --set ComputerName {{computer_name}}`

- Get hostname:

`scutil --get HostName`

- Set hostname:

`scutil --set HostName {{hostname}}`

