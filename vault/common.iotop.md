---
id: common.iotop
title: Iotop
desc: ''
updated: 1642441815035
created: 1642441815035
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# iotop

> Display a table of current I/O usage by processes or threads.
> More information: <https://manned.org/iotop>.

- Start top-like I/O monitor:

`sudo iotop`

- Show only processes or threads actually doing I/O:

`sudo iotop --only`

- Show I/O usage in non-interactive mode:

`sudo iotop --batch`

- Show only I/O usage of processes (default is to show all threads):

`sudo iotop --processes`

- Show I/O usage of given PID(s):

`sudo iotop --pid={{PID}}`

- Show I/O usage of a given user:

`sudo iotop --user={{user}}`

- Show accumulated I/O instead of bandwidth:

`sudo iotop --accumulated`

