---
id: common.rbac-lookup
title: Rbac Lookup
desc: ''
updated: 1615655543081
created: 1615655543081
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

