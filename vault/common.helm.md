---
id: common.helm
title: Helm
desc: ''
updated: 1623965016131
created: 1623965016131
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# helm

> Helm is a package manager for Kubernetes.
> More information: <https://helm.sh/>.

- Create a helm chart:

`helm create {{chart_name}}`

- Add a new helm repository:

`helm repo add {{repo_name}}`

- List helm repositories:

`helm repo list`

- Update helm repositories:

`helm repo update`

- Delete a helm repository:

`helm repo remove {{repo_name}}`

- Install a helm chart:

`helm install {{repo_name}}/{{chart_name}}`

- Download helm chart as a tar archive:

`helm get {{chart_release_name}}`

- Update helm dependencies:

`helm dependency update`

