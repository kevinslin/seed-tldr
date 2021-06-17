---
id: common.offlineimap
title: Offlineimap
desc: ''
updated: 1623965016141
created: 1623965016141
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# offlineimap

> Synchronize a remote IMAP server with local Maildir folders.
> More information: <http://www.offlineimap.org>.

- Synchronize once, without enabling autorefresh:

`offlineimap -o`

- Synchronize a specific account:

`offlineimap -a {{account}}`

- Synchronize a specific folder:

`offlineimap -f {{folder}}`

