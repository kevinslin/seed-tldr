---
id: linux.dockerd
title: Dockerd
desc: ''
updated: 1642441815092
created: 1642441815092
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dockerd

> A persistent process to start and manage docker containers.
> More information: <https://docs.docker.com/engine/reference/commandline/dockerd/>.

- Run docker daemon:

`dockerd`

- Run docker daemon and config it to listen to specific sockets (UNIX and TCP):

`dockerd --host unix://{{path/to/tmp.sock}} --host tcp://{{ip}}`

- Run with specific daemon PID file:

`dockerd --pidfile {{path/to/pid_file}}`

- Run in debug mode:

`dockerd --debug`

- Run and set a specific log level:

`dockerd --log-level={{debug|info|warn|error|fatal}}`

