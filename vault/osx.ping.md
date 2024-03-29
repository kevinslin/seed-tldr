---
id: osx.ping
title: Ping
desc: ''
updated: 1644840636311
created: 1644840636311
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ping

> Send ICMP ECHO_REQUEST packets to network hosts.
> More information: <https://ss64.com/osx/ping.html>.

- Ping the specified host:

`ping "{{hostname}}"`

- Ping a host a specific number of times:

`ping -c {{count}} "{{host}}"`

- Ping `host`, specifying the interval in `seconds` between requests (default is 1 second):

`ping -i {{seconds}} "{{host}}"`

- Ping `host` without trying to lookup symbolic names for addresses:

`ping -n "{{host}}"`

- Ping `host` and ring the bell when a packet is received (if your terminal supports it):

`ping -a "{{host}}"`

- Ping `host` and prints the time a packet was received (this option is an Apple addition):

`ping --apple-time "{{host}}"`

