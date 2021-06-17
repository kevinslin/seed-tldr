---
id: windows.cmstp
title: Cmstp
desc: ''
updated: 1623965306237
created: 1623965306237
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cmstp

> A command-line tool for managing connection service profiles.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/cmstp>.

- Install a specific profile:

`cmstp "{{path/to/profile}}"`

- Install without creating a desktop shortcut:

`cmstp /ns "{{path/to/profile}}"`

- Install without checking for dependencies:

`cmstp /nf "{{path/to/profile}}"`

- Only install for the current user:

`cmstp /su "{{path/to/profile}}"`

- Install for all users (requires administrator privileges):

`cmstp /au "{{path/to/profile}}"`

- Install silently without any prompts:

`cmstp /s "{{path/to/profile}}"`

- Uninstall a specific profile:

`cmstp /u "{{path/to/profile}}"`

- Uninstall silently without a confirmation prompt:

`cmstp /u /s "{{path/to/profile}}"`

