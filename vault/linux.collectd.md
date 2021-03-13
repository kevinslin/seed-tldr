---
id: linux.collectd
title: Collectd
desc: ''
updated: 1615655543097
created: 1615655543097
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# collectd

> System statistics collection daemon.
> More information: <https://collectd.org/>.

- Show usage help, including the program version:

`collectd -h`

- Test the configuration file and then exit:

`collectd -t`

- Test plugin data collection functionality and then exit:

`collectd -T`

- Start collectd:

`collectd`

- Specify a custom configuration file location:

`collectd -C {{path/to/file}}`

- Specify a custom PID file location:

`collectd -P {{path/to/file}}`

- Don't fork into the background:

`collectd -f`

