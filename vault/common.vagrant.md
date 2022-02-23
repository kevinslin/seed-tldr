---
id: common.vagrant
title: Vagrant
desc: ''
updated: 1645628512468
created: 1645628512468
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vagrant

> Manage lightweight, reproducible, and portable development environments.
> More information: <https://www.vagrantup.com>.

- Create Vagrantfile in current directory with the base Vagrant box:

`vagrant init`

- Create Vagrantfile with the Ubuntu 20.04 (Focal Fossa) box from HashiCorp Atlas:

`vagrant init ubuntu/focal64`

- Start and provision the vagrant environment:

`vagrant up`

- Suspend the machine:

`vagrant suspend`

- Halt the machine:

`vagrant halt`

- Connect to machine via SSH:

`vagrant ssh`

- Output the SSH configuration file of the running Vagrant machine:

`vagrant ssh-config`

- List all local boxes:

`vagrant box list`

