---
id: common.imapsync
title: Imapsync
desc: ''
updated: 1642441815035
created: 1642441815035
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# imapsync

> Email IMAP tool for syncing, copying and migrating email mailboxes between two IMAP servers, one way, and without duplicates.
> More information: <https://imapsync.lamiral.info>.

- Synchronize IMAP account between host1 and host2:

`imapsync --host1 {{host1}} --user1 {{user1}} --password1 {{secret1}} --host2 {{host2}} --user2 {{user2}} --password2 {{secret2}}`

