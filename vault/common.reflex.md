---
id: common.reflex
title: Reflex
desc: ''
updated: 1615655543081
created: 1615655543081
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# reflex

> Tool to watch a directory and rerun a command when certain files change.
> More information: <https://github.com/cespare/reflex>.

- Rebuild with `make` if any file changes:

`reflex make`

- Compile and run Go application if any `.go` file changes:

`reflex --regex='{{\.go$}}' {{go run .}}`

- Ignore a directory when watching for changes:

`reflex --inverse-regex='{{^dir/}}' {{command}}`

- Run command when reflex starts and restarts on file changes:

`reflex --start-service=true {{command}}`

- Substitute the filename that changed in:

`reflex -- echo {}`

