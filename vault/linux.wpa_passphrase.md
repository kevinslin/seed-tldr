---
id: linux.wpa_passphrase
title: Wpa_passphrase
desc: ''
updated: 1642441815117
created: 1642441815117
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wpa_passphrase

> Generate a WPA-PSK key from an ASCII passphrase for a given SSID.

- Compute and display the WPA-PSK key for a given SSID reading the passphrase from stdin:

`wpa_passphrase {{SSID}}`

- Compute and display WPA-PSK key for a given SSID specifying the passphrase as an argument:

`wpa_passphrase {{SSID}} {{passphrase}}`

