---
id: common.etcdctl
title: Etcdctl
desc: ''
updated: 1623965016123
created: 1623965016123
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# etcdctl

> CLI interface for interacting with etcd, a highly-available key-value pair store.
> More information: <https://etcd.io/docs/latest/dev-guide/interacting_v3/>.

- Display the value associated with a specified key:

`etcdctl get {{my/key}}`

- Store a key-value pair:

`etcdctl put {{my/key}} {{my_value}}`

- Delete a key-value pair:

`etcdctl del {{my/key}}`

- Store a key-value pair, reading the value from a file:

`etcdctl put {{my/file}} < {{path/to/file.txt}}`

- Save a snapshot of the etcd keystore:

`etcdctl snapshot save {{path/to/snapshot.db}}`

- Restore a snapshot of an etcd keystore (restart the etcd server afterwards):

`etcdctl snapshot restore {{path/to/snapshot.db}}`

- Add a user:

`etcdctl user add {{my_user}}`

- Watch a key for changes:

`etcdctl watch {{my/key}}`

