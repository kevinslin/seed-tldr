---
id: common.kubectl-rollout
title: Kubectl Rollout
desc: ''
updated: 1642441815040
created: 1642441815040
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kubectl rollout

> Manage the rollout of a Kubernetes resource (deployments, daemonsets, and statefulsets).
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#rollout>.

- Start a rolling restart of a resource:

`kubectl rollout restart {{resource_type}}/{{resource_name}}`

- Watch the rolling update status of a resource:

`kubectl rollout status {{resource_type}}/{{resource_name}}`

- Roll back a resource to the previous revision:

`kubectl rollout undo {{resource_type}}/{{resource_name}}`

- View the rollout history of a resource:

`kubectl rollout history {{resource_type}}/{{resource_name}}`

