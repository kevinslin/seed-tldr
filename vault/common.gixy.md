---
id: common.gixy
title: Gixy
desc: ''
updated: 1642441815028
created: 1642441815028
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

