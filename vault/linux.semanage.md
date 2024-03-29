---
id: linux.semanage
title: Semanage
desc: ''
updated: 1642441815112
created: 1642441815112
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# semanage

> SELinux Policy Management tool.
> More information: <https://manned.org/semanage>.

- Output local customizations:

`semanage -S {{store}} -o {{path/to/output_file}}`

- Take a set of commands from a specified file and load them in a single transaction:

`semanage -S {{store}} -i {{path/to/input_file}}`

- Manage booleans. Booleans allow the administrator to modify the confinement of processes based on the current configuration:

`semanage boolean -S {{store}} {{--delete|--modify|--list|--noheading|--deleteall}} {{-on|-off}} -F {{boolean|boolean_file}}`

- Manage policy modules:

`semanage module -S {{store}} {{--add|--delete|--list|--modify}} {{--enable|--disable}} {{module_name}}`

- Disable/Enable dontaudit rules in policy:

`semanage dontaudit -S {{store}} {{on|off}}`

