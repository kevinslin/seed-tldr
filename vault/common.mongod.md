---
id: common.mongod
title: Mongod
desc: ''
updated: 1615655543071
created: 1615655543071
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mongod

> The MongoDB database server.
> More information: <https://docs.mongodb.com/manual/reference/program/mongod>.

- Specify a config file:

`mongod --config {{filename}}`

- Specify the port to listen on:

`mongod --port {{port}}`

- Specify database profiling level. 0 is off, 1 is only slow operations, 2 is all:

`mongod --profile {{0|1|2}}`

