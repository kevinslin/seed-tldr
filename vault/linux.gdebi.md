---
id: linux.gdebi
title: Gdebi
desc: ''
updated: 1615655543101
created: 1615655543101
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# gdebi

> Simple tool to install `.deb` files.
> More information: <https://www.commandlinux.com/man-page/man1/gdebi.1.html>.

- Install local `.deb` packages resolving and installing its dependencies:

`gdebi {{path/to/package.deb}}`

- Display the program version:

`gdebi --version`

- Do not show progress information:

`gdebi {{path/to/package.deb}} --quiet`

- Set an APT configuration option:

`gdebi {{path/to/package.deb}} --option={{APT_OPTS}}`

- Use alternative root dir:

`gdebi {{path/to/package.deb}} --root={{path/to/root_dir}}`

