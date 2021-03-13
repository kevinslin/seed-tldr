---
id: common.ncmpcpp
title: Ncmpcpp
desc: ''
updated: 1615663978726
created: 1615663978726
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ncmpcpp

> A command line music player client for the Music Player Daemon.
> More information: <https://rybczak.net/ncmpcpp>.

- Connect to a music player daemon on a given host and port:

`ncmpcpp --host {{ip}} --port {{port}}`

- Display metadata of the current song to console:

`ncmpcpp --current-song`

- Use a specified configuration file:

`ncmpcpp --config {{file}}`

- Use a different set of key bindings from a file:

`ncmpcpp --bindings {{file}}`

