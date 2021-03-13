---
id: common.kompose
title: Kompose
desc: ''
updated: 1615655543066
created: 1615655543066
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

