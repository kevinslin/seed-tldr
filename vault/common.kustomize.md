---
id: common.kustomize
title: Kustomize
desc: ''
updated: 1615655543066
created: 1615655543066
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# kustomize

> Kustomize is a tool to easily deploy resources for Kubernetes.
> More information: <https://github.com/kubernetes-sigs/kustomize>.

- Create kustomization file with resources and namespace:

`kustomize create --resources {{deployment.yaml,service.yaml}} --namespace {{staging}}`

- Build kustomization file and deploy it with `kubectl`:

`kustomize build . | kubectl apply -f -`

- Set an image in the kustomization file:

`kustomize edit set image {{busybox=alpine:3.6}}`

- Search for kubernetes resources in the current directory to be added to the kustomization file:

`kustomize create --autodetect`

