---
id: common.hive
title: Hive
desc: ''
updated: 1615655543063
created: 1615655543063
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

