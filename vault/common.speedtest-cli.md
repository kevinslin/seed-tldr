---
id: common.speedtest-cli
title: Speedtest CLI
desc: ''
updated: 1623965016150
created: 1623965016150
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# speedtest-cli

> Unofficial command-line interface for testing internet bandwidth using <https://speedtest.net.>
> See also `speedtest` for the official CLI.
> More information: <https://github.com/sivel/speedtest-cli>.

- Run a speed test:

`speedtest-cli`

- Run a speed test and display values in bytes, instead of bits:

`speedtest-cli --bytes`

- Run a speed test using `HTTPS`, instead of `HTTP`:

`speedtest-cli --secure`

- Run a speed test without performing download tests:

`speedtest-cli --no-download`

- Run a speed test and generate an image of the results:

`speedtest-cli --share`

- List all `speedtest.net` servers, sorted by distance:

`speedtest-cli --list`

- Run a speed test to a specific speedtest.net server:

`speedtest-cli --server {{server_id}}`

- Run a speed test and display the results as JSON (suppresses progress information):

`speedtest-cli --json`

