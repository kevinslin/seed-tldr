---
id: common.mongoimport
title: Mongoimport
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
# mongoimport

> Imports content from a JSON, CSV, or TSV file into a MongoDB database.
> More information: <https://docs.mongodb.com/database-tools/mongoimport/>.

- Import a JSON file into a specific collection:

`mongoimport --file={{path/to/file.json}} --uri={{mongodb_uri}} --collection={{collection_name}}`

- Import a CSV file, using the first line of the file to determine field names:

`mongoimport --type={{csv}} --file={{path/to/file.csv}} --db={{database_name}} --collection={{collection_name}}`

- Import a JSON array, using each element as a separate document:

`mongoimport --jsonArray --file={{path/to/file.json}}`

- Import a JSON file using a specific mode and a query to match existing documents:

`mongoimport --file={{path/to/file.json}} --mode={{delete|merge|upsert}} --upsertFields="{{field1,field2,...}}"`

- Import a CSV file, reading field names from a separate CSV file and ignoring fields with empty values:

`mongoimport --type={{csv}} --file={{path/to/file.csv}} --fieldFile={{path/to/field_file.csv}} --ignoreBlanks`

- Display help:

`mongoimport --help`

