---
id: common.aws-quicksight
title: Aws Quicksight
desc: ''
updated: 1642441814996
created: 1642441814996
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# aws quicksight

> CLI for AWS QuickSight.
> Access QuickSight entities.
> More information: <https://docs.aws.amazon.com/cli/latest/reference/quicksight/>.

- List datasets:

`aws quicksight list-data-sets --aws-account-id {{aws_account_id}}`

- List users:

`aws quicksight list-users --aws-account-id {{aws_account_id}} --namespace default`

- List groups:

`aws quicksight list-groups --aws-account-id {{aws_account_id}} --namespace default`

- List dashboards:

`aws quicksight list-dashboards --aws-account-id {{aws_account_id}}`

- Display detailed information about a dataset:

`aws quicksight describe-data-set --aws-account-id {{aws_account_id}} --data-set-id {{data_set_id}}`

- Display who has access to the dataset and what kind of actions they can perform on the dataset:

`aws quicksight describe-data-set-permissions --aws-account-id {{aws_account_id}} --data-set-id {{data_set_id}}`

