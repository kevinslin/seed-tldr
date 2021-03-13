---
id: common.darkhttpd
title: Darkhttpd
desc: ''
updated: 1615655543050
created: 1615655543050
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# darkhttpd

> Darkhttpd web server.
> More information: <https://unix4lyfe.org/darkhttpd>.

- Start server serving the specified document root:

`darkhttpd {{path/to/docroot}}`

- Start server on specified port (port 8080 by default if running as non-root user):

`darkhttpd {{path/to/docroot}} --port {{port}}`

- Listen only on specified IP address (by default, the server listens on all interfaces):

`darkhttpd {{path/to/docroot}} --addr {{ip_address}}`

