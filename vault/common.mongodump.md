---
id: common.mongodump
title: Mongodump
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
# mongodump

> Utility to export the contents of a MongoDB instance.
> More information: <https://docs.mongodb.com/database-tools/mongodump/>.

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

- Create a dump from a specific instance; host, user, password and database will be defined in the connection string:

`mongodump --uri {{connection_string}}`

