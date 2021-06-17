---
id: linux.iw
title: Iw
desc: ''
updated: 1623965016163
created: 1623965016163
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iw

> Show and manipulate wireless devices.

- Scan for available wireless networks:

`iw dev {{wlp}} scan`

- Join an open wireless network:

`iw dev {{wlp}} connect {{SSID}}`

- Close the current connection:

`iw dev {{wlp}} disconnect`

- Show information about the current connection:

`iw dev {{wlp}} link`

