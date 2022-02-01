---
id: common.sv
title: Sv
desc: ''
updated: 1642441815074
created: 1642441815074
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sv

> Control a running runsv service.
> More information: <https://manpages.ubuntu.com/manpages/latest/man8/sv.8.html>.

- Start a service:

`sudo sv up {{path/to/service}}`

- Stop a service:

`sudo sv down {{path/to/service}}`

- Get service status:

`sudo sv status {{path/to/service}}`

- Reload a service:

`sudo sv reload {{path/to/service}}`

- Start a service, but only if it's not running and don't restart it if it stops:

`sudo sv once {{path/to/service}}`

