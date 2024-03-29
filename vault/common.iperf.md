---
id: common.iperf
title: Iperf
desc: ''
updated: 1642441815036
created: 1642441815036
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iperf

> Measure network bandwidth between computers.
> More information: <https://iperf.fr>.

- Run on server:

`iperf -s`

- Run on server using UDP mode and set server port to listen on 5001:

`iperf -u -s -p {{5001}}`

- Run on client:

`iperf -c {{server_address}}`

- Run on client every 2 seconds:

`iperf -c {{server_address}} -i {{2}}`

- Run on client with 5 parallel threads:

`iperf -c {{server_address}} -P {{5}}`

- Run on client using UDP mode:

`iperf -u -c {{server_address}} -p {{5001}}`

