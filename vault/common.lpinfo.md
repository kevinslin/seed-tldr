---
id: common.lpinfo
title: Lpinfo
desc: ''
updated: 1642441815043
created: 1642441815043
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lpinfo

> List connected printers and installed drivers for the CUPS print server.
> More information: <https://www.cups.org/doc/man-lpinfo.html>.

- List all the currently connected printers:

`lpinfo -v`

- List all the currently installed printer drivers:

`lpinfo -m`

- Search installed printer drivers by make and model:

`lpinfo --make-and-model "{{printer_model}}" -m`

