---
id: osx.csshx
title: Csshx
desc: ''
updated: 1615663978759
created: 1615663978759
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# csshX

> Cluster SSH tool for MacOS.
> More information: <https://github.com/brockgr/csshx>.

- Connect to multiple hosts:

`csshX {{hostname1}} {{hostname2}}`

- Connect to multiple hosts with a given SSH key:

`csshX {{user@hostname1}} {{user@hostname2}} '--ssh_args' '-i {{path/to/ssh_key.pem}}'`

- Connect to a pre-defined cluster from `/etc/clusters`:

`csshX cluster1`

