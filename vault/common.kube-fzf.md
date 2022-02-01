---
id: common.kube-fzf
title: Kube Fzf
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
# kube-fzf

> Shell commands for command-line fuzzy searching of Kubernetes Pods.
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

