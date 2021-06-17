---
id: common.mongo
title: Mongo
desc: ''
updated: 1623965016136
created: 1623965016136
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

- Evaluate a JavaScript expression on the database:

`mongo --eval '{{JSON.stringify(db.foo.findOne())}}' {{database}}`

