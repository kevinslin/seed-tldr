---
id: common.ansible-galaxy
title: Ansible Galaxy
desc: ''
updated: 1623965306173
created: 1623965306173
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ansible-galaxy

> Create and manage Ansible roles.
> More information: <https://docs.ansible.com/ansible/latest/cli/ansible-galaxy.html>.

- Install a role:

`ansible-galaxy install {{username.role_name}}`

- Remove a role:

`ansible-galaxy remove {{username.role_name}}`

- List installed roles:

`ansible-galaxy list`

- Search for a given role:

`ansible-galaxy search {{role_name}}`

- Create a new role:

`ansible-galaxy init {{role_name}}`

