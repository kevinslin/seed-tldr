---
id: common.iperf3
title: Iperf3
desc: ''
updated: 1615663978720
created: 1615663978720
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iperf3

> Traffic generator for testing network bandwidth.
> More information: <https://iperf.fr>.

- Run iperf3 as a server:

`iperf3 -s`

- Run an iperf3 server on a specific port:

`iperf3 -s -p {{port}}`

- Start bandwidth test:

`iperf3 -c {{server}}`

- Run iperf3 in multiple parallel streams:

`iperf3 -c {{server}} -P {{streams}}`

- Reverse direction of the test. Server sends data to the client:

`iperf3 -c {{server}} -R`

