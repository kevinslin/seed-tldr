---
id: common.go-list
title: Go List
desc: ''
updated: 1615655543060
created: 1615655543060
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# go list

> List packages or modules.
> More information: <https://golang.org/cmd/go/#hdr-List_packages_or_modules>.

- List packages:

`go list ./...`

- List standard packages:

`go list std`

- List packages in json format:

`go list -json time net/http`

- List module dependencies and available updates:

`go list -m -u all`

