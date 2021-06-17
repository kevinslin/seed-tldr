---
id: osx.airport
title: Airport
desc: ''
updated: 1623965306232
created: 1623965306232
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# airport

> Wireless network configuration utility.

- Show current wireless status information:

`airport -I`

- Sniff wireless traffic on channel 1:

`airport sniff {{1}}`

- Scan for available wireless networks:

`airport -s`

- Disassociate from current airport network:

`sudo airport -z`

