---
id: common.prosodyctl
title: Prosodyctl
desc: ''
updated: 1642441815061
created: 1642441815061
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# prosodyctl

> The control tool for the Prosody XMPP server.
> More information: <https://prosody.im/doc/prosodyctl>.

- Show the status of the Prosody server:

`sudo prosodyctl status`

- Reload the server's configuration files:

`sudo prosodyctl reload`

- Add a user to the Prosody XMPP server:

`sudo prosodyctl adduser {{user@example.com}}`

- Set a user's password:

`sudo prosodyctl passwd {{user@example.com}}`

- Permanently delete a user:

`sudo prosodyctl deluser {{user@example.com}}`

