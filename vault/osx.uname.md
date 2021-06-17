---
id: osx.uname
title: Uname
desc: ''
updated: 1623965306236
created: 1623965306236
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# uname

> Print details about the current machine and the operating system running on it.
> Note: for additional information about the operating system, try the `sw_vers` command.

- Print hardware-related information: machine and processor:

`uname -mp`

- Print software-related information: operating system, release number, and version:

`uname -srv`

- Print the nodename (hostname) of the system:

`uname -n`

- Print all available system information (hardware, software, nodename):

`uname -a`

