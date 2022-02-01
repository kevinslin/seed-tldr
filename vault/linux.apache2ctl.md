---
id: linux.apache2ctl
title: Apache2ctl
desc: ''
updated: 1642441815087
created: 1642441815087
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# apache2ctl

> The CLI tool to administrate HTTP web server Apache.
> This command comes with Debian based OSes, for RHEL based ones see `httpd`.
> More information: <https://manpages.debian.org/latest/apache2/apache2ctl.8.en.html>.

- Start the Apache daemon. Throw a message if it is already running:

`sudo apache2ctl start`

- Stop the Apache daemon:

`sudo apache2ctl stop`

- Restart the Apache daemon:

`sudo apache2ctl restart`

- Test syntax of the configuration file:

`sudo apache2ctl -t`

- List loaded modules:

`sudo apache2ctl -M`

