---
id: osx.airport
title: Airport
desc: ''
updated: 1644840636305
created: 1644840636305
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# airport

> Wireless network configuration utility.
> More information: <https://ss64.com/osx/airport.html>.

- Show current wireless status information:

`airport --getinfo`

- Sniff wireless traffic on channel 1:

`airport sniff {{1}}`

- Scan for available wireless networks:

`airport --scan`

- Disassociate from current airport network:

`sudo airport --disassociate`

