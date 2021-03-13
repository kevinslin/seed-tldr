---
id: common.mongodump
title: Mongodump
desc: ''
updated: 1615655543071
created: 1615655543071
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# mongodump

> Utility to export the contents of a MongoDB instance.
> More information: <https://docs.mongodb.com/manual/reference/program/mongodump>.

- Create a dump of all databases (this will place the files inside a directory called "dump"):

`mongodump`

- Specify an output location for the dump:

`mongodump --out {{path/to/directory}}`

- Create a dump of a given database:

`mongodump --db {{database_name}}`

- Create a dump of a given collection within a given database:

`mongodump --collection {{collection_name}} --db {{database_name}}`

- Connect to a given host running on a given port, and create a dump:

`mongodump --host {{host}} --port {{port}}`

- Create a dump of a given database with a given username; user will be prompted for password:

`mongodump --username {{username}} {{database}} --password`

