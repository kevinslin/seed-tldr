---
id: common.mongoexport
title: Mongoexport
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
# mongoexport

> Produce exports of data stored in a MongoDB instance formatted as JSON or CSV.
> More information: <https://docs.mongodb.com/database-tools/mongoexport/>.

- Export a collection to stdout, formatted as JSON:

`mongoexport --uri={{connection_string}} --collection={{collection_name}}`

- Export the documents in the specified collection that match a query to a JSON file:

`mongoexport --db={{database_name}} --collection={{collection_name}} --query="{{query_object}}" --out={{path/to/file.json}}`

- Export documents as a JSON array instead of one object per line:

`mongoexport --collection={{collection_name}} --jsonArray`

- Export documents to a CSV file:

`mongoexport --collection={{collection_name}} --type={{csv}} --fields="{{field1,field2,...}}" --out={{path/to/file.csv}}`

- Export documents that match the query in the specified file to a CSV file, omitting the list of field names on the first line:

`mongoexport --collection={{collection_name}} --type={{csv}} --fields="{{field1,field2,...}}" --queryFile={{path/to/file}} --noHeaderLine --out={{path/to/file.csv}}`

- Export documents to stdout, formatted as human-readable JSON:

`mongoexport --uri={{mongodb_uri}} --collection={{collection_name}} --pretty`

- Display help:

`mongoexport --help`

