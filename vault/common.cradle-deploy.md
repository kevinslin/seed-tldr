---
id: common.cradle-deploy
title: Cradle Deploy
desc: ''
updated: 1623965016117
created: 1623965016117
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

