---
id: common.kubectl-delete
title: Kubectl Delete
desc: ''
updated: 1645329705600
created: 1645329705600
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kubectl delete

> Delete Kubernetes resources.
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#delete>.

- Delete a specific pod:

`kubectl delete pod {{pod_name}}`

- Delete a specific deployment:

`kubectl delete deployment {{deployment_name}}`

- Delete a specific node:

`kubectl delete node {{node_name}}`

- Delete all pods in a specified namespace:

`kubectl delete pods --all --namespace {{namespace}}`

- Delete all deployments and services in a specified namespace:

`kubectl delete deployments,services --all --namespace {{namespace}}`

- Delete all nodes:

`kubectl delete nodes --all`

- Delete resources defined in a YAML manifest:

`kubectl delete --filename {{path/to/manifest.yaml}}`

