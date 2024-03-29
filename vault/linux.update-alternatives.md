---
id: linux.update-alternatives
title: Update Alternatives
desc: ''
updated: 1642441815115
created: 1642441815115
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# update-alternatives

> A convenient tool for maintaining symbolic links to determine default commands.
> More information: <https://manned.org/update-alternatives>.

- Add a symbolic link:

`sudo update-alternatives --install {{path/to/symlink}} {{command_name}} {{path/to/command_binary}} {{priority}}`

- Configure a symbolic link for `java`:

`sudo update-alternatives --config {{java}}`

- Remove a symbolic link:

`sudo update-alternatives --remove {{java}} {{/opt/java/jdk1.8.0_102/bin/java}}`

- Display information about a specified command:

`update-alternatives --display {{java}}`

- Display all commands and their current selection:

`update-alternatives --get-selections`

