---
id: linux.cryptsetup
title: Cryptsetup
desc: ''
updated: 1623965306220
created: 1623965306220
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cryptsetup

> Manage plain dm-crypt and LUKS (Linux Unified Key Setup) encrypted volumes.

- Initialize a LUKS volume (overwrites all data on the partition):

`cryptsetup luksFormat {{/dev/sda1}}`

- Open a LUKS volume and create a decrypted mapping at `/dev/mapper/{{target}}`:

`cryptsetup luksOpen {{/dev/sda1}} {{target}}`

- Remove an existing mapping:

`cryptsetup luksClose {{target}}`

- Change the LUKS volume's passphrase:

`cryptsetup luksChangeKey {{/dev/sda1}}`

