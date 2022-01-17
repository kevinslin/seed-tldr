---
id: common.hive
title: Hive
desc: ''
updated: 1642441815033
created: 1642441815033
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hive

> CLI tool for Apache Hive.
> More information: <https://cwiki.apache.org/confluence/display/Hive/LanguageManual+Cli>.

- Start a Hive interactive shell:

`hive`

- Run HiveQL:

`hive -e "{{hiveql_query}}"`

- Run a HiveQL file with a variable substitution:

`hive --define {{key}}={{value}} -f {{path/to/file.sql}}`

- Run a HiveQL with HiveConfig (e.g. `mapred.reduce.tasks=32`):

`hive --hiveconf {{conf_name}}={{conf_value}}`

