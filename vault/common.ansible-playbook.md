---
id: common.ansible-playbook
title: Ansible Playbook
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
# ansible-playbook

> Execute tasks defined in playbook on remote machines over SSH.
> More information: <https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html>.

- Run tasks in playbook:

`ansible-playbook {{playbook}}`

- Run tasks in playbook with custom host inventory:

`ansible-playbook {{playbook}} -i {{inventory_file}}`

- Run tasks in playbook with extra variables defined via the command-line:

`ansible-playbook {{playbook}} -e "{{variable1}}={{value1}} {{variable2}}={{value2}}"`

- Run tasks in playbook with extra variables defined in a JSON file:

`ansible-playbook {{playbook}} -e "@{{variables.json}}"`

- Run tasks in playbook for the given tags:

`ansible-playbook {{playbook}} --tags {{tag1,tag2}}`

- Run tasks in a playbook starting at a specific task:

`ansible-playbook {{playbook}} --start-at {{task_name}}`

