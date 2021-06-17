---
id: sunos.svcadm
title: Svcadm
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
# svcadm

> Manipulate service instances.
> More information: <https://www.unix.com/man-page/linux/1m/svcadm>.

- Enable a service in the service database:

`svcadm enable {{service_name}}`

- Disable service:

`svcadm disable {{service_name}}`

- Restart a running service:

`svcadm restart {{service_name}}`

- Command service to re-read configuration files:

`svcadm refresh {{service_name}}`

- Clear a service from maintenance state and command it to start:

`svcadm clear {{service_name}}`

