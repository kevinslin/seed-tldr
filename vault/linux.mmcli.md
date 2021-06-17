---
id: linux.mmcli
title: Mmcli
desc: ''
updated: 1623965306226
created: 1623965306226
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mmcli

> Control and monitor the ModemManager.
> More information: <https://www.freedesktop.org/software/ModemManager/man/latest/mmcli.1.html>.

- List SMS messages available on the modem:

`sudo mmcli --modem={{modem}} --messaging-list-sms`

- Delete a message from the modem, specifying its path:

`sudo mmcli --modem={{modem}} --messaging-delete-sms={{path/to/message_file}}`

