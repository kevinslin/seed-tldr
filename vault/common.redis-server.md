---
id: common.redis-server
title: Redis Server
desc: ''
updated: 1615655543081
created: 1615655543081
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

