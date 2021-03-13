---
id: common.aws-vault
title: Aws Vault
desc: ''
updated: 1615655543045
created: 1615655543045
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# aws-vault

> A vault for securely storing and accessing AWS credentials in development environments.
> More information: <https://github.com/99designs/aws-vault>.

- Add credentials to the secure keystore:

`aws-vault add {{profile}}`

- Execute a command with AWS credentials in the environment:

`aws-vault exec {{profile}} -- {{aws s3 ls}}`

- Open a browser window and login to the AWS Console:

`aws-vault login {{profile}}`

- List profiles, along with their credentials and sessions:

`aws-vault list`

- Rotate AWS credentials:

`aws-vault rotate {{profile}}`

- Remove credentials from the secure keystore:

`aws-vault remove {{profile}}`

