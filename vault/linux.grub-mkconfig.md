---
id: linux.grub-mkconfig
title: Grub Mkconfig
desc: ''
updated: 1623965016162
created: 1623965016162
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

