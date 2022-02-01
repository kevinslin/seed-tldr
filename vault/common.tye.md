---
id: common.tye
title: Tye
desc: ''
updated: 1642441815078
created: 1642441815078
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tye

> Developer tool that makes developing, testing, and deploying microservices and distributed applications easier.
> More information: <https://github.com/dotnet/tye>.

- Scaffold a `tye.yaml` file representing the application:

`tye init`

- Run an application locally:

`tye run`

- Build an application's containers:

`tye build`

- Push an application's containers:

`tye push`

- Deploy an application to Kubernetes:

`tye deploy`

- Remove a deployed application from Kubernetes:

`tye undeploy`

