---
id: common.jq
title: Jq
desc: ''
updated: 1647061311391
created: 1647061311391
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jq

> A command-line JSON processor that uses a domain-specific language.
> More information: <https://stedolan.github.io/jq>.

- Output a JSON file, in pretty-print format:

`jq . {{file.json}}`

- Output all elements from arrays (or all the values from objects) in a JSON file:

`jq '.[]' {{file.json}}`

- Output elements from arrays which match provided filter:

`jq '.[] | select(.{{key_name}} == {{value}})'`

- Read JSON objects from a file into an array, and output it (inverse of `jq .[]`):

`jq --slurp . {{file.json}}`

- Output the first element in a JSON file:

`jq '.[0]' {{file.json}}`

- Output the value of a given key of each element in a JSON text from stdin:

`cat {{file.json}} | jq 'map(.{{key_name}})'`

- Output the value of multiple keys as a new JSON object (assuming the input JSON has the keys `key_name` and `other_key_name`):

`cat {{file.json}} | jq '{{{my_new_key}}: .{{key_name}}, {{my_other_key}}: .{{other_key_name}}}'`

- Output the value of a given key to a string (and disable JSON output):

`cat {{file.json}} | jq --raw-output '"some text: \(.{{key_name}})"'`

