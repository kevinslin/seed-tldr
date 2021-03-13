---
id: common.kube-fzf
title: Kube Fzf
desc: ''
updated: 1615655543066
created: 1615655543066
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# kube-fzf

> Shell commands for command line fuzzy searching of Kubernetes Pods.
> See also `kubectl` for related commands.
> More information: <https://github.com/thecasualcoder/kube-fzf>.

- Get pod details (from current namespace):

`findpod`

- Get pod details (from all namespaces):

`findpod -a`

- Describe a pod:

`describepod`

- Tail pod logs:

`tailpod`

- Exec into a pod's container:

`execpod {{shell_command}}`

- Port-forward a pod:

`pfpod {{port_number}}`

