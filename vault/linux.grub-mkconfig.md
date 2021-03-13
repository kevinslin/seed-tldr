---
id: linux.grub-mkconfig
title: Grub Mkconfig
desc: ''
updated: 1615655543102
created: 1615655543102
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# grub-mkconfig

> Generate a GRUB configuration file.
> More information: <https://www.gnu.org/software/grub/manual/grub/html_node/Invoking-grub_002dmkconfig.html>.

- Do a dry run and print the configuration to stdout:

`sudo grub-mkconfig`

- Generate the configuration file:

`sudo grub-mkconfig --output={{/boot/grub/grub.cfg}}`

- Print the help page:

`grub-mkconfig --help`

