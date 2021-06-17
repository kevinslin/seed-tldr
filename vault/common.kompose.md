---
id: common.kompose
title: Kompose
desc: ''
updated: 1623965016134
created: 1623965016134
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kompose

> A tool to convert docker-compose applications to Kubernetes.
> More information: <https://github.com/kubernetes/kompose>.

- Deploy a dockerized application to Kubernetes:

`kompose up -f {{docker-compose.yml}}`

- Delete instantiated services/deployments from Kubernetes:

`kompose down -f {{docker-compose.yml}}`

- Convert a docker-compose file into Kubernetes resources file:

`kompose convert -f {{docker-compose.yml}}`

