---
id: common.odps-tunnel
title: Odps Tunnel
desc: ''
updated: 1615655543076
created: 1615655543076
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

