---
id: osx.vpnd
title: Vpnd
desc: ''
updated: 1644840636313
created: 1644840636313
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vpnd

> Listens for incoming VPN connections.
> It should not be invoked manually.
> More information: <https://www.unix.com/man-page/osx/8/vpnd/>.

- Start the daemon:

`vpnd`

- Run the daemon in the foreground:

`vpnd -x`

- Run the daemon in the foreground and print logs to the terminal:

`vpnd -d`

- Run the daemon in the foreground, print logs to the terminal, and quit after validating arguments:

`vpnd -n`

- Print usage summary and exit:

`vpnd -h`

- Run the daemon for a specific server configuration:

`vpnd -i {{server_id}}`

