---
id: common.odps-tunnel
title: Odps Tunnel
desc: ''
updated: 1615663978727
created: 1615663978727
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# odps tunnel

> Data tunnel in ODPS (Open Data Processing Service).

- Download table to local file:

`tunnel download {{table_name}} {{file}};`

- Upload local file to a table partition:

`tunnel upload {{file}} {{table_name}}/{{partition_spec}};`

- Upload table specifying field and record delimiters:

`tunnel upload {{file}} {{table_name}} -fd {{field_delim}} -rd {{record_delim}};`

- Upload table using multiple threads:

`tunnel upload {{file}} {{table_name}} -threads {{num}};`

