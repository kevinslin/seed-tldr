---
id: common.ykinfo
title: Ykinfo
desc: ''
updated: 1642441815085
created: 1642441815085
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ykinfo

> Get basic information from a YubiKey.
> More information: <https://developers.yubico.com/yubikey-personalization/Manuals/ykinfo.1.html>.

- Display all information from YubiKey:

`ykinfo -a`

- Get only serial in decimal from YubiKey:

`ykinfo -s -q`

- Get capabilities from YubiKey:

`ykinfo -c`

