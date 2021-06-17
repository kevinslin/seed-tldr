---
id: linux.lshw
title: Lshw
desc: ''
updated: 1623965306225
created: 1623965306225
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lshw

> List detailed information about hardware configurations as root user.

- Launch the GUI:

`sudo lshw -X`

- List all hardwares in tabular format:

`sudo lshw -short`

- List all disks and storage controllers in tabular format:

`sudo lshw -class disk -class storage -short`

- Save all network interfaces to an HTML file:

`sudo lshw -class network -html > {{interfaces.html}}`

