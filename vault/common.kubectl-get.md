---
id: common.kubectl-get
title: Kubectl Get
desc: ''
updated: 1642441815039
created: 1642441815039
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kubectl get

> Get Kubernetes objects and resources.
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#get>.

- Get all namespaces in the current cluster:

`kubectl get namespaces`

- Get nodes in a specified namespace:

`kubectl get nodes -n {{namespace}}`

- Get pods in a specified namespace:

`kubectl get pods -n {{namespace}}`

- Get deployments in a specified namespace:

`kubectl get deployments -n {{namespace}}`

- Get services in a specified namespace:

`kubectl get services -n {{namespace}}`

- Get all resources in a specified namespace:

`kubectl get all -n {{namespace}}`

- Get Kubernetes objects defined in a YAML manifest:

`kubectl get -f {{path/to/manifest}}.yaml`

