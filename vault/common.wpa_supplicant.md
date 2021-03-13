---
id: common.wpa_supplicant
title: Wpa_supplicant
desc: ''
updated: 1615655543093
created: 1615655543093
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# wpa_supplicant

> Manage protected wireless networks.

- Join a protected wireless network:

`wpa_supplicant -i {{interface}} -c {{path/to/wpa_supplicant_conf.conf}}`

- Join a protected wireless network and run it in a daemon:

`wpa_supplicant -B -i {{interface}} -c {{path/to/wpa_supplicant_conf.conf}}`

