---
id: common.k8s-unused-secret-detector
title: K8s Unused Secret Detector
desc: ''
updated: 1615655543066
created: 1615655543066
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

