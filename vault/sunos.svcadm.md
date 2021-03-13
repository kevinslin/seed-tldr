---
id: sunos.svcadm
title: Svcadm
desc: ''
updated: 1615663978762
created: 1615663978762
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# svcadm

> Manipulate service instances.

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

