---
id: common.cradle-elastic
title: Cradle Elastic
desc: ''
updated: 1623965306178
created: 1623965306178
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cradle elastic

> Manage the ElasticSearch instances for a Cradle instance.
> More information: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#elastic>.

- Truncate the ElasticSearch index:

`cradle elastic flush`

- Truncate the ElasticSearch index for a specific package:

`cradle elastic flush {{package_name}}`

- Submit the ElasticSearch schema:

`cradle elastic map`

- Submit the ElasticSearch schema for a specific package:

`cradle elastic map {{package_name}}`

- Populate the ElasticSearch indices for all packages:

`cradle elastic populate`

- Populate the ElasticSearch indices for a specific package:

`cradle elastic populate {{package_name}}`

