---
id: common.mosquitto
title: Mosquitto
desc: ''
updated: 1615655543071
created: 1615655543071
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

