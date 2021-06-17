---
id: common.kube-capacity
title: Kube Capacity
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
# kube-capacity

> A simple CLI that provides an overview of the resource requests, limits, and utilization in a Kubernetes cluster.
> Combine the best parts of `kubectl top` and `kubectl describe` into a CLI focused on cluster resources.
> More information: <https://github.com/robscott/kube-capacity>.

- Output a list of nodes with the total CPU and Memory resource requests and limits:

`kube-capacity`

- Include pods:

`kube-capacity -p`

- Include utilization:

`kube-capacity -u`

