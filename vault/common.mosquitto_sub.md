---
id: common.mosquitto_sub
title: Mosquitto_sub
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
# mosquitto_sub

> A simple MQTT version 3.1.1 client that will subscribe to topics and print the messages that it receives.
> More information: <https://mosquitto.org/man/mosquitto_sub-1.html>.

- Subscribe to the topic `sensors/temperature` information with Quality of Service (`QoS`) set to 1. (The default hostname is `localhost` and port 1883):

`mosquitto_sub -t {{sensors/temperature}} -q {{1}}`

- Subscribe to all broker status messages publishing on `iot.eclipse.org` port 1885 and print published messages verbosely:

`mosquitto_sub -v -h "iot.eclipse.org" -p 1885 -t {{\$SYS/#}}`

- Subscribe to multiple topics matching a given pattern. (+ takes any metric name):

`mosquitto_sub -t {{sensors/machines/+/temperature/+}}`

