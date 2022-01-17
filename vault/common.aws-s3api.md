---
id: common.aws-s3api
title: Aws S3api
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
# aws s3api

> Create and delete Amazon S3 buckets and edit bucket properties.
> More information: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3api/index.html>.

- Create a bucket:

`aws s3api create-bucket --bucket {{bucket_name}}`

- Delete a bucket:

`aws s3api delete-bucket --bucket {{bucket_name}}`

- List buckets:

`aws s3api list-buckets`

- List the objects inside of a bucket and only show each object's key and size:

`aws s3api list-objects --bucket {{bucket_name}} --query '{{Contents[].{Key: Key, Size: Size}}}'`

- Add an object to a bucket:

`aws s3api put-object --bucket {{bucket_name}} --key {{object_key}} --body {{path/to/file}}`

- Download object from a bucket (The output file is always the last argument):

`aws s3api get-object --bucket {{bucket_name}} --key {{object_key}} {{path/to/output_file}}`

- Apply an Amazon S3 bucket policy to a specified bucket:

`aws s3api put-bucket-policy --bucket {{bucket_name}} --policy file://{{path/to/bucket_policy.json}}`

- Download the Amazon S3 bucket policy from a specified bucket:

`aws s3api get-bucket-policy --bucket {{bucket_name}} --query Policy --output {{json|table|text|yaml|yaml-stream}} > {{path/to/bucket_policy}}`

