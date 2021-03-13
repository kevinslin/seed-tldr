---
id: common.hostapd
title: Hostapd
desc: ''
updated: 1615663978718
created: 1615663978718
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hostapd

> Start an access point using a wireless interface.
> More information: <https://w1.fi/hostapd/>.

- Start an access point:

`sudo hostapd {{path/to/hostapd.conf}}`

- Start an access point, forking into the background:

`sudo hostapd -B {{path/to/hostapd.conf}}`

