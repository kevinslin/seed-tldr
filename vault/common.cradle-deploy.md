---
id: common.cradle-deploy
title: Cradle Deploy
desc: ''
updated: 1615655543049
created: 1615655543049
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# cradle deploy

> Manage Cradle deployments.
> More information: <https://cradlephp.github.io/docs/3.B.-Reference-Command-Line-Tools.html#deploy>.

- Deploy Cradle to a server:

`cradle deploy production`

- Deploy static assets to Amazon S3:

`cradle deploy s3`

- Deploy static assets including the Yarn "components" directory:

`cradle deploy s3 --include-yarn`

- Deploy static assets including the "upload" directory:

`cradle deploy s3 --include-upload`

