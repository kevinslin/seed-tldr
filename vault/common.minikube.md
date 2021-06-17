---
id: common.minikube
title: Minikube
desc: ''
updated: 1623965016136
created: 1623965016136
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# minikube

> Tool to run Kubernetes locally.
> More information: <https://github.com/kubernetes/minikube>.

- Start the cluster:

`minikube start`

- Get the IP address of the cluster:

`minikube ip`

- Access a service named my_service exposed via a node port and get the URL:

`minikube service {{my_service}} --url`

- Open the Kubernetes dashboard in a browser:

`minikube dashboard`

- Stop the running cluster:

`minikube stop`

- Delete the cluster:

`minikube delete`

