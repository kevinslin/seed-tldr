---
id: linux.auracle
title: Auracle
desc: ''
updated: 1615655543096
created: 1615655543096
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# auracle

> Command line tool used to interact with Arch Linux's User Repository, commonly referred to as the AUR.
> More information: <https://github.com/falconindy/auracle>.

- Display AUR packages that match a regular expression:

`auracle search '{{regex}}'`

- Display package information for a space-separated list of AUR packages:

`auracle info {{package1}} {{package2}}`

- Display the `PKGBUILD` file (build information) for a space-separated list of AUR packages:

`auracle show {{package1}} {{package2}}`

- Display updates for installed AUR packages:

`auracle outdated`

