---
id: common.hadolint
title: Hadolint
desc: ''
updated: 1623965016131
created: 1623965016131
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# hadolint

> Dockerfile linter.
> More information: <https://github.com/hadolint/hadolint>.

- Lint a Dockerfile:

`hadolint {{path/to/Dockerfile}}`

- Lint a Dockerfile, displaying the output in JSON format:

`hadolint --format {{json}} {{path/to/Dockerfile}}`

- Lint a Dockerfile, displaying the output in a specific format:

`hadolint --format {{tty|json|checkstyle|codeclimate|codacy}} {{path/to/Dockerfile}}`

- Lint a Dockerfile ignoring specific rules:

`hadolint --ignore {{DL3006}} --ignore {{DL3008}} {{path/to/Dockerfile}}`

- Lint multiple Dockerfiles using specific trusted registries:

`hadolint --trusted-registry {{docker.io}} --trusted-registry {{example.com}}:{{5000}} {{path/to/Dockerfile}} {{path/to/another/Dockerfile}}`

