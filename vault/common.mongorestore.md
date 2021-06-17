---
id: common.mongorestore
title: Mongorestore
desc: ''
updated: 1623965306197
created: 1623965306197
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# mongorestore

> Utility to import a collection or database from a binary dump into a MongoDB instance.
> More information: <https://docs.mongodb.com/database-tools/mongorestore/>.

- Import a bson data dump from a directory to a MongoDB database:

`mongorestore --db {{database_name}} {{path/to/directory}}`

- Import a bson data dump from a directory to a given database in a MongoDB server host, running at a given port, with user authentication (user will be prompted for password):

`mongorestore --host {{database_host:port}} --db {{database_name}} --username {{username}} {{path/to/directory}} --password`

- Import a collection from a bson file to a MongoDB database:

`mongorestore --db {{database_name}} {{path/to/file}}`

- Import a collection from a bson file to a given database in a MongoDB server host, running at a given port, with user authentication (user will be prompted for password):

`mongorestore --host {{database_host:port}} --db {{database_name}} --username {{username}} {{path/to/file}} --password`

