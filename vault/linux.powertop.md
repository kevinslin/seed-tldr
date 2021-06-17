---
id: linux.powertop
title: Powertop
desc: ''
updated: 1623965016167
created: 1623965016167
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# powertop

> Optimize battery power usage.

- Calibrate power usage measurements:

`sudo powertop --calibrate`

- Generate HTML power usage report in the current directory:

`sudo powertop --html={{power_report.html}}`

- Tune to optimal settings:

`sudo powertop --auto-tune`

