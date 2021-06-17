---
id: linux.acpi
title: Acpi
desc: ''
updated: 1623965306218
created: 1623965306218
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# acpi

> Shows battery status or thermal information.
> More information: <https://sourceforge.net/projects/acpiclient/files/acpiclient/>.

- Show battery information:

`acpi`

- Show thermal information:

`acpi -t`

- Show cooling device information:

`acpi -c`

- Show thermal information in Fahrenheit:

`acpi -tf`

- Show all information:

`acpi -V`

- Extract information from `/proc` instead of `/sys`:

`acpi -p`

