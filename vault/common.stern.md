---
id: common.stern
title: Stern
desc: ''
updated: 1642441815071
created: 1642441815071
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# stern

> Tail multiple pods and containers from Kubernetes.
> More information: <https://github.com/wercker/stern/>.

- Tail all pods within a current namespace:

`stern .`

- Tail all pods with a specific status:

`stern . --container-state {{running|waiting|terminated}}`

- Tail all pods that matches a given regular expression:

`stern {{pod_query}}`

- Tail matched pods from all namespaces:

`stern {{pod_query}} --all-namespaces`

- Tail matched pods from 15 minutes ago:

`stern {{pod_query}} --since {{15m}}`

- Tail matched pods with a specific label:

`stern {{pod_query}} --selector {{release=canary}}`

