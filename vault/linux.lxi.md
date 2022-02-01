---
id: linux.lxi
title: Lxi
desc: ''
updated: 1642441815102
created: 1642441815102
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# lxi

> Control LXI compatible instruments such as oscilloscopes.
> More information: <https://github.com/lxi-tools/lxi-tools>.

- Discover LXI devices on available networks:

`lxi discover`

- Capture a screenshot, detecting a plugin automatically:

`lxi screenshot --address {{ip_address}}`

- Capture a screenshot using a specified plugin:

`lxi screenshot --address {{ip_address}} --plugin {{rigol-1000z}}`

- Send an SCPI command to an instrument:

`lxi scpi --address {{ip_address}} "{{*IDN?}}"`

- Run a benchmark for request and response performance:

`lxi benchmark --address {{ip_address}}`

