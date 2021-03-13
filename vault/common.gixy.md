---
id: common.gixy
title: Gixy
desc: ''
updated: 1615655543060
created: 1615655543060
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# gixy

> Analyze nginx configuration files.
> More information: <https://github.com/yandex/gixy>.

- Analyze nginx configuration (default path: `/etc/nginx/nginx.conf`):

`gixy`

- Analyze nginx configuration but skip specific tests:

`gixy --skips {{http_splitting}}`

- Analyze nginx configuration with the specific severity level:

`gixy {{-l|-ll|-lll}}`

- Analyze nginx configuration files on the specific path:

`gixy {{path/to/configuration_file_1}} {{path/to/configuration_file_2}}`

