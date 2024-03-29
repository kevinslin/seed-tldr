---
id: common.ansible-pull
title: Ansible Pull
desc: ''
updated: 1642441814994
created: 1642441814994
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ansible-pull

> Pull ansible playbooks from a VCS repo and executes them for the local host.
> More information: <https://docs.ansible.com/ansible/latest/cli/ansible-pull.html>.

- Pull a playbook from a VCS and execute a default local.yml playbook:

`ansible-pull -U {{repository_url}}`

- Pull a playbook from a VCS and execute a specific playbook:

`ansible-pull -U {{repository_url}} {{playbook}}`

- Pull a playbook from a VCS at a specific branch and execute a specific playbook:

`ansible-pull -U {{repository_url}} -C {{branch}} {{playbook}}`

- Pull a playbook from a VCS, specify hosts file and execute a specific playbook:

`ansible-pull -U {{repository_url}} -i {{hosts_file}} {{playbook}}`

