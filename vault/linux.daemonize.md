---
id: linux.daemonize
title: Daemonize
desc: ''
updated: 1623965016160
created: 1623965016160
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# daemonize

> Run a command (that does not daemonize itself) as a Unix daemon.
> More information: <http://software.clapper.org/daemonize/>.

- Run a command as a daemon:

`daemonize {{command}} {{command_arguments}}`

- Write the pid to the specified file:

`daemonize -p {{path/to/pidfile}} {{command}} {{command_arguments}}`

- Use a lock file to ensure that only one instance runs at a time:

`daemonize -l {{path/to/lockfile}} {{command}} {{command_arguments}}`

- Use the specified user account:

`sudo daemonize -u {{user}} {{command}} {{command_arguments}}`

