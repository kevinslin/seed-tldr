---
id: common.cradle-elastic
title: Cradle Elastic
desc: ''
updated: 1615655543049
created: 1615655543049
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

