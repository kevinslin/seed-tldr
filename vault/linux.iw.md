---
id: linux.iw
title: Iw
desc: ''
updated: 1642441815100
created: 1642441815100
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iw

> Show and manipulate wireless devices.
> More information: <https://manned.org/iw>.

- Scan for available wireless networks:

`iw dev {{wlp}} scan`

- Join an open wireless network:

`iw dev {{wlp}} connect {{SSID}}`

- Close the current connection:

`iw dev {{wlp}} disconnect`

- Show information about the current connection:

`iw dev {{wlp}} link`

