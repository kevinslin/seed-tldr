---
id: common.timeout
title: Timeout
desc: ''
updated: 1623965306213
created: 1623965306213
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# timeout

> Run a command with a time limit.
> More information: <https://www.gnu.org/software/coreutils/timeout>.

- Run `sleep 10` and terminate it, if it runs for more than 3 seconds:

`timeout {{3s}} {{sleep 10}}`

- Specify the signal to be sent to the command after the time limit expires. (By default, TERM is sent):

`timeout --signal {{INT}} {{5s}} {{sleep 10}}`

