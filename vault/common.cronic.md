---
id: common.cronic
title: Cronic
desc: ''
updated: 1615663978704
created: 1615663978704
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cronic

> Bash script for wrapping cron jobs to prevent excess email sending.
> More information: <https://habilis.net/cronic/>.

- Call a command and display its output if it returns a non-zero exit code:

`cronic {{command}}`

