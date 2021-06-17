---
id: common.popeye
title: Popeye
desc: ''
updated: 1623965306205
created: 1623965306205
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# popeye

> Utility that reports potential issues with Kubernetes deployment manifests.
> More information: <https://github.com/derailed/popeye>.

- Scan the current Kubernetes cluster:

`popeye`

- Scan a specific namespace:

`popeye -n {{namespace}}`

- Scan specific Kubernetes context:

`popeye --context={{context}}`

- Use a spinach configuration file for scanning:

`popeye -f {{spinach.yaml}}`

