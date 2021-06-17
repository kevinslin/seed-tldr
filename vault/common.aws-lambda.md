---
id: common.aws-lambda
title: Aws Lambda
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
# aws lambda

> CLI for AWS lambda.
> More information: <https://docs.aws.amazon.com/cli/latest/reference/lambda/>.

- Run a function:

`aws lambda invoke --function-name {{name}} {{path/to/response}}.json`

- Run a function with an input payload in JSON format:

`aws lambda invoke --function-name {{name}} --payload {{json}} {{path/to/response}}.json`

- List functions:

`aws lambda list-functions`

- Display the configuration of a function:

`aws lambda get-function-configuration --function-name {{name}}`

- List function aliases:

`aws lambda list-aliases --function-name {{name}}`

- Display the reserved concurrency configuration for a function:

`aws lambda get-function-concurrency --function-name {{name}}`

- List which AWS services can invoke the function:

`aws lambda get-policy --function-name {{name}}`

