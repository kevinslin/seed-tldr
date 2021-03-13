---
id: linux.acpi
title: Acpi
desc: ''
updated: 1615655543095
created: 1615655543095
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

