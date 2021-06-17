---
id: common.aws-glue
title: Aws Glue
desc: ''
updated: 1623965306174
created: 1623965306174
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aws glue

> CLI for AWS Glue.
> Defines the public endpoint for the AWS Glue service.
> More information: <https://docs.aws.amazon.com/cli/latest/reference/glue/>.

- List jobs:

`aws glue list-jobs`

- Start a job:

`aws glue start-job-run --job-name {{job_name}}`

- Start running a workflow:

`aws glue start-workflow-run --name {{workflow_name}}`

- List triggers:

`aws glue list-triggers`

- Start a trigger:

`aws glue start-trigger --name {{trigger_name}}`

- Create a dev endpoint:

`aws glue create-dev-endpoint --endpoint-name {{name}} --role-arn {{role_arn_used_by_endpoint}}`

