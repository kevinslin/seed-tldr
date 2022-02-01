---
id: linux.lshw
title: Lshw
desc: ''
updated: 1642441815102
created: 1642441815102
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lshw

> List detailed information about hardware configurations as root user.
> More information: <https://manned.org/lshw>.

- Launch the GUI:

`sudo lshw -X`

- List all hardware in tabular format:

`sudo lshw -short`

- List all disks and storage controllers in tabular format:

`sudo lshw -class disk -class storage -short`

- Save all network interfaces to an HTML file:

`sudo lshw -class network -html > {{interfaces.html}}`

