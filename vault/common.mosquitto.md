---
id: common.mosquitto
title: Mosquitto
desc: ''
updated: 1623965016137
created: 1623965016137
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

