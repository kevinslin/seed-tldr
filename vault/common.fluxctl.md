---
id: common.fluxctl
title: Fluxctl
desc: ''
updated: 1642441815018
created: 1642441815018
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fluxctl

> Command-line tool for Flux v1.
> More information: <https://fluxcd.io/legacy/flux/references/fluxctl>.

- List workloads currently running in the cluster on specific namespace:

`fluxctl --k8s-fwd-ns={{namespace}} list-workloads`

- Show deployed and available images:

`fluxctl list-images`

- Synchronize the cluster with the git repository:

`fluxctl sync`

- Turn on automatic deployment for a workload:

`fluxctl automate`

