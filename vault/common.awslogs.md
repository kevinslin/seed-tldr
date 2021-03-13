---
id: common.awslogs
title: Awslogs
desc: ''
updated: 1615655543045
created: 1615655543045
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# awslogs

> Queries groups, streams and events from Amazon Cloudwatch logs.
> More information: <https://github.com/jorgebastida/awslogs>.

- List log groups:

`awslogs groups`

- List existing streams for the specified group:

`awslogs streams {{/var/log/syslog}}`

- Get logs for any streams in the specified group between 1 and 2 hours ago:

`awslogs get {{/var/log/syslog}} --start='{{2h ago}}' --end='{{1h ago}}'`

- Get logs that match a specific Cloudwatch Logs Filter pattern:

`awslogs get {{/aws/lambda/my_lambda_group}} --filter-pattern='{{ERROR}}'`

- Watch logs for any streams in the specified group:

`awslogs get {{/var/log/syslog}} ALL --watch`

