---
id: common.odps
title: Odps
desc: ''
updated: 1642441815053
created: 1642441815053
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# odps

> Aliyun ODPS (Open Data Processing Service) command-line tool.
> Some subcommands such as `odps inst` have their own usage documentation.
> More information: <https://www.alibabacloud.com/help/doc-detail/27971.htm>.

- Start the command-line with a custom configuration file:

`odpscmd --config={{odps_config.ini}}`

- Switch current project:

`use {{project_name}};`

- Show tables in the current project:

`show tables;`

- Describe a table:

`desc {{table_name}};`

- Show table partitions:

`show partitions {{table_name}};`

- Describe a partition:

`desc {{table_name}} partition ({{partition_spec}});`

