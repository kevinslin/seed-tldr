---
id: common.nginx
title: Nginx
desc: ''
updated: 1615655543074
created: 1615655543074
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# nginx

> Nginx web server.
> More information: <https://nginx.org/en/>.

- Start server with the default config file:

`nginx`

- Start server with a custom config file:

`nginx -c {{config_file}}`

- Start server with a prefix for all relative paths in the config file:

`nginx -c {{config_file}} -p {{prefix/for/relative/paths}}`

- Test the configuration without affecting the running server:

`nginx -t`

- Reload the configuration by sending a signal with no downtime:

`nginx -s reload`

