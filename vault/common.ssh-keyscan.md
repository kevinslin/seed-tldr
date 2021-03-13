---
id: common.ssh-keyscan
title: Ssh Keyscan
desc: ''
updated: 1615663978735
created: 1615663978735
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ssh-keyscan

> Get the public ssh keys of remote hosts.

- Retrieve all public ssh keys of a remote host:

`ssh-keyscan {{host}}`

- Retrieve all public ssh keys of a remote host listening on a specific port:

`ssh-keyscan -p {{port}} {{host}}`

- Retrieve certain types of public ssh keys of a remote host:

`ssh-keyscan -t {{rsa,dsa,ecdsa,ed25519}} {{host}}`

- Manually update the ssh known_hosts file with the fingerprint of a given host:

`ssh-keyscan -H {{host}} >> ~/.ssh/known_hosts`

