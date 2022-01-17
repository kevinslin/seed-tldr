---
id: osx.csshx
title: Csshx
desc: ''
updated: 1642441815120
created: 1642441815120
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csshX

> Cluster SSH tool for macOS.
> More information: <https://github.com/brockgr/csshx>.

- Connect to multiple hosts:

`csshX {{hostname1}} {{hostname2}}`

- Connect to multiple hosts with a given SSH key:

`csshX {{user@hostname1}} {{user@hostname2}} '--ssh_args' '-i {{path/to/ssh_key.pem}}'`

- Connect to a pre-defined cluster from `/etc/clusters`:

`csshX cluster1`

