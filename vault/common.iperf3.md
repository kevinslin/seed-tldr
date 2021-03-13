---
id: common.iperf3
title: Iperf3
desc: ''
updated: 1615655543064
created: 1615655543064
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

