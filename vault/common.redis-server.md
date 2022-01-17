---
id: common.redis-server
title: Redis Server
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# redis-server

> Persistent key-value database.
> More information: <https://redis.io>.

- Start Redis server, using the default port (6379), and write logs to stdout:

`redis-server`

- Start Redis server, using the default port, as a background process:

`redis-server --daemonize yes`

- Start Redis server, using the specified port, as a background process:

`redis-server --port {{port}} --daemonize yes`

- Start Redis server with a custom configuration file:

`redis-server {{path/to/redis.conf}}`

- Start Redis server with verbose logging:

`redis-server --loglevel {{warning|notice|verbose|debug}}`

