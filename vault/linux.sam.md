---
id: linux.sam
title: Sam
desc: ''
updated: 1623965016168
created: 1623965016168
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sam

> AWS Serverless Application Model (SAM) CLI.
> More information: <https://github.com/awslabs/aws-sam-cli>.

- Initialize a serverless application:

`sam init`

- Initialize a serverless application with a specific runtime:

`sam init --runtime {{python3.7}}`

- Package a SAM application:

`sam package`

- Build your Lambda function code:

`sam build`

- Run your serverless application locally:

`sam local start-api`

- Deploy an AWS SAM application:

`sam deploy`

