---
id: common.offlineimap
title: Offlineimap
desc: ''
updated: 1642441815053
created: 1642441815053
stub: false
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

