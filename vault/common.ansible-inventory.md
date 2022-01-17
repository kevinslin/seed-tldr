---
id: common.ansible-inventory
title: Ansible Inventory
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
# ansible-inventory

> Display or dump an Ansible inventory.
> See also: `ansible`.
> More information: <https://docs.ansible.com/ansible/latest/cli/ansible-inventory.html>.

- Display the default inventory:

`ansible-inventory --list`

- Display a custom inventory:

`ansbile-inventory --list --inventory {{path/to/file_or_script_or_directory}}`

- Display the default inventory in YAML:

`ansible-inventory --list --yaml`

- Dump the default inventory to a file:

`ansible-inventory --list --output {{path/to/file}}`

