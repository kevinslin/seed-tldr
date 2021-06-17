---
id: linux.openfortivpn
title: Openfortivpn
desc: ''
updated: 1623965306226
created: 1623965306226
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# openfortivpn

> A VPN client, for Fortinet's proprietary PPP+SSL VPN solution.
> More information: <https://github.com/adrienverge/openfortivpn>.

- Connect to a VPN with a username and password:

`openfortivpn --username={{username}} --password={{password}}`

- Connect to a VPN using a specific configuration file (defaults to `/etc/openfortivpn/config`):

`sudo openfortivpn --config={{path/to/config}}`

- Connect to a VPN by specifying the host and port:

`openfortivpn {{host}}:{{port}}`

- Trust a given gateway by passing in its certificate's sha256 sum:

`openfortivpn --trusted-cert={{sha256_sum}}`

