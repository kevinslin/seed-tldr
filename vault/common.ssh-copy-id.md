---
id: common.ssh-copy-id
title: Ssh Copy Id
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ssh-copy-id

> Install your public key in a remote machine's authorized_keys.
> More information: <https://manned.org/ssh-copy-id>.

- Copy your keys to the remote machine:

`ssh-copy-id {{username@remote_host}}`

- Copy the given public key to the remote:

`ssh-copy-id -i {{path/to/certificate}} {{username}}@{{remote_host}}`

- Copy the given public key to the remote with specific port:

`ssh-copy-id -i {{path/to/certificate}} -p {{port}} {{username}}@{{remote_host}}`

