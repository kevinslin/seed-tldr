---
id: common.kind
title: Kind
desc: ''
updated: 1642441815038
created: 1642441815038
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kind

> Tool for running local Kubernetes clusters using Docker container "nodes".
> Designed for testing Kubernetes itself, but may be used for local development or continuous integration.
> More information: <https://github.com/kubernetes-sigs/kind>.

- Create a local Kubernetes cluster:

`kind create cluster --name {{cluster_name}}`

- Delete one or more clusters:

`kind delete clusters {{cluster_name}}`

- Get details about clusters, nodes, or the kubeconfig:

`kind get {{clusters|nodes|kubeconfig}}`

- Export the kubeconfig or the logs:

`kind export {{kubeconfig|logs}}`

