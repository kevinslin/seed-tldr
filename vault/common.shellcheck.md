---
id: common.shellcheck
title: Shellcheck
desc: ''
updated: 1615655543085
created: 1615655543085
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# shellcheck

> Shell script static analysis tool.
> More information: <https://www.shellcheck.net/>.

- Check a shell script:

`shellcheck {{file.sh}}`

- Override script's shebang:

`shellcheck --shell {{sh|bash|ksh}} {{file.sh}}`

- Ignore certain errors:

`shellcheck --exclude {{SC1009}} {{file.sh}}`

- Ignore multiple errors:

`shellcheck --exclude {{SC1009,SC1073}} {{file.sh}}`

