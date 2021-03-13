---
id: common.kops
title: Kops
desc: ''
updated: 1615663978721
created: 1615663978721
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kops

> Create, destroy, upgrade and maintain Kubernetes clusters from the command line.
> More information: <https://github.com/kubernetes/kops/>.

- Create a cluster from the configuration specification:

`kops create cluster -f {{cluster_name.yaml}}`

- Create a new ssh public key:

`kops create secret sshpublickey {{key_name}} -i {{~/.ssh/id_rsa.pub}}`

- Export the cluster configuration to the `~/.kube/config` file:

`kops export kubecfg {{cluster_name}}`

- Get the cluster configuration as yaml:

`kops get cluster {{cluster_name}} -o yaml`

- Delete a cluster:

`kops delete cluster {{cluster_name}} --yes`

