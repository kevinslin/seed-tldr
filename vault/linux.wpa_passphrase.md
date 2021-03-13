---
id: linux.wpa_passphrase
title: Wpa_passphrase
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# wpa_passphrase

> Generate a WPA-PSK key from an ASCII passphrase for a given SSID.

- Compute and display the WPA-PSK key for a given SSID reading the passphrase from stdin:

`wpa_passphrase {{SSID}}`

- Compute and display WPA-PSK key for a given SSID specifying the passphrase as an argument:

`wpa_passphrase {{SSID}} {{passphrase}}`

