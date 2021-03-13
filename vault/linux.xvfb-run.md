---
id: linux.xvfb-run
title: Xvfb Run
desc: ''
updated: 1615655543112
created: 1615655543112
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# xvfb-run

> Run a command in a virtual X server environment.
> More information: <https://www.x.org/wiki/>.

- Run the specified command in a virtual X server:

`xvfb-run {{command}}`

- Try to get a free server number, if the default (99) is not available:

`xvfb-run --auto-servernum {{command}}`

- Pass arguments to the Xvfb server:

`xvfb-run --server-args "{{-screen 0 1024x768x24}}" {{command}}`

