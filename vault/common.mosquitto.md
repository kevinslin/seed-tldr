---
id: common.mosquitto
title: Mosquitto
desc: ''
updated: 1642441815048
created: 1642441815048
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mosquitto

> An MQTT broker.
> More information: <https://mosquitto.org/>.

- Start mosquitto:

`mosquitto`

- Specify a configuration file to use:

`mosquitto --config-file {{path/to/file.conf}}`

- Listen on a specific port:

`mosquitto --port {{8883}}`

- Daemonize by forking into the background:

`mosquitto --daemon`

