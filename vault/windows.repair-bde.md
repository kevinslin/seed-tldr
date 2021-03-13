---
id: windows.repair-bde
title: Repair Bde
desc: ''
updated: 1615655543119
created: 1615655543119
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# repair-bde

> Attempt to repair or decrypt a damaged BitLocker-encrypted volume.
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/repair-bde>.

- Attempt to repair a specified volume:

`repair-bde {{C:}}`

- Attempt to repair a specified volume and output to another volume:

`repair-bde {{C:}} {{D:}}`

- Attempt to repair a specified volume using the provided recovery key file:

`repair-bde {{C:}} -RecoveryKey {{path/to/file.bek}}`

- Attempt to repair a specified volume using the provided numerical recovery password:

`repair-bde {{C:}} -RecoveryPassword {{password}}`

- Attempt to repair a specified volume using the provided password:

`repair-bde {{C:}} -Password {{password}}`

- Attempt to repair a specified volume using the provided key package:

`repair-bde {{C:}} -KeyPackage {{path/to/directory}}`

- Log all output to a specific file:

`repair-bde {{C:}} -LogFile {{path/to/file}}`

- Display all available options:

`repair-bde /?`

