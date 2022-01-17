---
id: common.rbac-lookup
title: Rbac Lookup
desc: ''
updated: 1642441815064
created: 1642441815064
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rbac-lookup

> Find roles and cluster roles attached to any user, service account or group name in your Kubernetes cluster.
> More information: <https://github.com/reactiveops/rbac-lookup>.

- View all RBAC bindings:

`rbac-lookup`

- View RBAC bindings that match a given expression:

`rbac-lookup {{search_term}}`

- View all RBAC bindings along with the source role binding:

`rbac-lookup -o wide`

- View all RBAC bindings filtered by subject:

`rbac-lookup -k {{user|group|serviceaccount}}`

- View all RBAC bindings along with IAM roles (if you are using GKE):

`rbac-lookup --gke`

