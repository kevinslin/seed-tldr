---
id: common.guacd
title: Guacd
desc: ''
updated: 1615663978718
created: 1615663978718
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# guacd

> Apache Guacamole proxy daemon.
> Support loader for client plugins to interface between the Guacamole protocol and any arbitrary remote desktop protocol (e.g. RDP, VNC, Other).
> More information: <https://guacamole.apache.org/>.

- Bind to a specific port on localhost:

`guacd -b {{127.0.0.1}} -l {{4823}}`

- Start in debug mode, keeping the process in the foreground:

`guacd -f -L {{debug}}`

- Start with TLS support:

`guacd -C {{my-cert.crt}} -K {{my-key.pem}}`

- Write the PID to a file:

`guacd -p {{path/to/file.pid}}`

