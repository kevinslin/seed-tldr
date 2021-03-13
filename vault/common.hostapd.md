---
id: common.hostapd
title: Hostapd
desc: ''
updated: 1615655543063
created: 1615655543063
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# hostapd

> Start an access point using a wireless interface.
> More information: <https://w1.fi/hostapd/>.

- Start an access point:

`sudo hostapd {{path/to/hostapd.conf}}`

- Start an access point, forking into the background:

`sudo hostapd -B {{path/to/hostapd.conf}}`

