---
id: linux.ddrescue
title: Ddrescue
desc: ''
updated: 1623965016160
created: 1623965016160
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ddrescue

> Data recovery tool that reads data from damaged block devices.
> More information: <https://www.gnu.org/software/ddrescue/>.

- Take an image of a device, creating a log file:

`sudo ddrescue {{/dev/sdb}} {{path/to/image.dd}} {{path/to/log.txt}}`

- Clone Disk A to Disk B, creating a log file:

`sudo ddrescue --force --no-scrape {{/dev/sdX}} {{/dev/sdY}} {{path/to/log.txt}}`

