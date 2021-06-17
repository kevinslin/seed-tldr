---
id: common.aws-s3
title: Aws S3
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
# aws s3

> CLI for AWS S3 - provides storage through web services interfaces.
> More information: <https://aws.amazon.com/cli>.

- Show files in a bucket:

`aws s3 ls {{bucket_name}}`

- Sync files and directories from local to bucket:

`aws s3 sync {{path/to/files}} s3://{{bucket_name}}`

- Sync files and directories from bucket to local:

`aws s3 sync s3://{{bucket_name}} {{path/to/target}}`

- Sync files and directories with exclusions:

`aws s3 sync {{path/to/files}} s3://{{bucket_name}} --exclude {{path/to/file}} --exclude {{path/to/directory}}/*`

- Remove file from bucket:

`aws s3 rm s3://{{bucket}}/{{path/to/file}}`

- Preview changes only:

`aws s3 {{any_command}} --dryrun`

