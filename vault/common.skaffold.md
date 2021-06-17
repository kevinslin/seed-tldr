---
id: common.skaffold
title: Skaffold
desc: ''
updated: 1623965306210
created: 1623965306210
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# skaffold

> A tool that facilitates continuous development for Kubernetes applications.
> More information: <https://skaffold.dev>.

- Build the artifacts:

`skaffold build -f {{skaffold.yaml}}`

- Build and deploy your app every time your code changes:

`skaffold dev -f {{skaffold.yaml}}`

- Run a pipeline file:

`skaffold run -f {{skaffold.yaml}}`

- Run a diagnostic on Skaffold:

`skaffold diagnose -f {{skaffold.yaml}}`

- Deploy the artifacts:

`skaffold deploy -f {{skaffold.yaml}}`

