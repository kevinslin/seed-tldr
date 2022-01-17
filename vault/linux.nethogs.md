---
id: linux.nethogs
title: Nethogs
desc: ''
updated: 1642441815105
created: 1642441815105
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# nethogs

> Monitor bandwidth usage per process.
> More information: <https://github.com/raboof/nethogs>.

- Start nethogs as root (default device is eth0):

`sudo nethogs`

- Monitor bandwidth on specific device:

`sudo nethogs {{device}}`

- Monitor bandwidth on multiple devices:

`sudo nethogs {{device1}} {{device2}}`

- Specify refresh rate:

`sudo nethogs -t {{seconds}}`

