---
id: common.k8s-unused-secret-detector
title: K8s Unused Secret Detector
desc: ''
updated: 1615663978721
created: 1615663978721
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# k8s-unused-secret-detector

> Command line interface tool for detecting unused Kubernetes secrets.
> More information: <https://github.com/dtan4/k8s-unused-secret-detector>.

- Detect unused secrets:

`k8s-unused-secret-detector`

- Detect unused secrets in a specific namespace:

`k8s-unused-secret-detector -n {{namespace}}`

- Delete unused secrets in a specific namespace:

`k8s-unused-secret-detector -n {{namespace}} | kubectl delete secret -n {{namespace}}`

