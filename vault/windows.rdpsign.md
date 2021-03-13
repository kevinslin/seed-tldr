---
id: windows.rdpsign
title: Rdpsign
desc: ''
updated: 1615663978763
created: 1615663978763
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rdpsign

> A tool for signing Remote Desktop Protocol (RDP) files.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/rdpsign>.

- Sign an RDP file:

`rdpsign {{path/to/file.rdp}}`

- Sign an RDP file using a specific sha256 hash:

`rdpsign {{path/to/file.rdp}} /sha265 {{hash}}`

- Enable quiet output:

`rdpsign {{path/to/file.rdp}} /q`

- Display verbose warnings, messages and statuses:

`rdpsign {{path/to/file.rdp}} /v`

- Test the signing by displaying the output to stdout without updating the file:

`rdpsign {{path/to/file.rdp}} /l`

