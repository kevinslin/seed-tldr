---
id: linux.pihole
title: Pihole
desc: ''
updated: 1642441815108
created: 1642441815108
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pihole

> Terminal interface for the Pi-hole ad-blocking DNS server.
> More information: <https://pi-hole.net>.

- Check the Pi-hole daemon's status:

`pihole status`

- Update Pi-hole:

`pihole updatePihole`

- Monitor detailed system status:

`pihole chronometer`

- Start or stop the daemon:

`pihole {{enable|disable}}`

- Restart the daemon (not the server itself):

`pihole restartdns`

- Whitelist or blacklist a domain:

`pihole {{whitelist|blacklist}} {{example.com}}`

- Search the lists for a domain:

`pihole query {{example.com}}`

- Open a real-time log of connections:

`pihole tail`

