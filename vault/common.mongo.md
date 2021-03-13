---
id: common.mongo
title: Mongo
desc: ''
updated: 1615655543071
created: 1615655543071
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mongo

> MongoDB interactive shell client.
> More information: <https://docs.mongodb.com/manual/reference/program/mongo>.

- Connect to a database:

`mongo {{database}}`

- Connect to a database running on a given host on a given port:

`mongo --host {{host}} --port {{port}} {{database}}`

- Connect to a database with a given username; user will be prompted for password:

`mongo --username {{username}} {{database}} --password`

- Evaluate a javascript expression on the database:

`mongo --eval '{{JSON.stringify(db.foo.findOne())}}' {{database}}`

