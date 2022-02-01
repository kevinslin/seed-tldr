---
id: common.script
title: Script
desc: ''
updated: 1642441815067
created: 1642441815067
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# script

> Make a typescript file of a terminal session.
> More information: <https://manned.org/script>.

- Start recording in file named "typescript":

`script`

- Stop recording:

`exit`

- Start recording in a given file:

`script {{logfile.log}}`

- Append to an existing file:

`script -a {{logfile.log}}`

- Execute quietly without start and done messages:

`script -q {{logfile.log}}`

