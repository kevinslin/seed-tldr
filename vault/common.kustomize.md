---
id: common.kustomize
title: Kustomize
desc: ''
updated: 1642441815040
created: 1642441815040
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

- Search for Kubernetes resources in the current directory to be added to the kustomization file:

`kustomize create --autodetect`

