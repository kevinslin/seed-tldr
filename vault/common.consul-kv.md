---
id: common.consul-kv
title: Consul Kv
desc: ''
updated: 1642441815004
created: 1642441815004
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# consul-kv

> Distributed key-value store with health checking and service discovery.
> More information: <https://learn.hashicorp.com/consul/getting-started/kv>.

- Read a value from the key-value store:

`consul kv get {{key}}`

- Store a new key-value pair:

`consul kv put {{key}} {{value}}`

- Delete a key-value pair:

`consul kv delete {{key}}`

