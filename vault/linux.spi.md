---
id: linux.spi
title: Spi
desc: ''
updated: 1615655543109
created: 1615655543109
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# spi

> A meta package manager that handles both packages and slackbuilds.
> More information: <https://github.com/gapan/spi>.

- Update the list of available packages and slackbuilds:

`spi --update`

- Install a package or slackbuild:

`spi --install {{package/slackbuild_name}}`

- Upgrade all installed packages to the latest versions available:

`spi --upgrade`

- Locate packages or slackbuilds of interest by package name or description:

`spi {{search_terms}}`

- Display information about a package or slackbuild:

`spi --show {{package/slackbuild_name}}`

- Purge the local package and slackbuild caches:

`spi --clean`

