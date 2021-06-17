---
id: windows.wsl
title: Wsl
desc: ''
updated: 1623965016178
created: 1623965016178
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wsl

> Manage the Windows Subsystem for Linux from the command-line.
> More information: <https://docs.microsoft.com/windows/wsl/reference>.

- Start a Linux shell (in the default distribution):

`wsl {{shell_command}}`

- Run a Linux command without using a shell:

`wsl --exec {{command}} {{command_arguments}}`

- Specify a particular distribution:

`wsl --distribution {{distribution}} {{shell_command}}`

- List available distributions:

`wsl --list`

- Export a distribution to a `.tar` file:

`wsl --export {{distribution}} {{path/to/distro_fs.tar}}`

- Import a distribution from a `.tar` file:

`wsl --import {{distribution}} {{path/to/install_location}} {{path/to/distro_fs.tar}}`

- Change the version of the specified distribution:

`wsl --set-version {{distribution}} {{version}}`

- Shut down Windows Subsystem for Linux:

`wsl --shutdown`

