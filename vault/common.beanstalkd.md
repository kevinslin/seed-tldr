---
id: common.beanstalkd
title: Beanstalkd
desc: ''
updated: 1623965306175
created: 1623965306175
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# beanstalkd

> A simple and generic work-queue server.
> More information: <https://beanstalkd.github.io/>.

- Start beanstalkd, listening on port 11300:

`beanstalkd`

- Start beanstalkd listening on a custom port and address:

`beanstalkd -l {{ip_address}} -p {{port_number}}`

- Persist work queues by saving them to disk:

`beanstalkd -b {{path/to/persistence_directory}}`

- Sync to the persistence directory every 500 milliseconds:

`beanstalkd -b {{path/to/persistence_directory}} -f {{500}}`

