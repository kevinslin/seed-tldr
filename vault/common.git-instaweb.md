---
id: common.git-instaweb
title: Git Instaweb
desc: ''
updated: 1615663978713
created: 1615663978713
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git instaweb

> Helper to launch a gitweb server.
> More information: <https://git-scm.com/docs/git-instaweb>.

- Launch a gitweb server for the current Git repository:

`git instaweb --start`

- Listen only on localhost:

`git instaweb --start --local`

- Listen on a specific port:

`git instaweb --start --port {{1234}}`

- Use a specified http daemon:

`git instaweb --start --httpd {{lighttpd|apache2|mongoose|plackup|webrick}}`

- Also auto-launch a web browser:

`git instaweb --start --browser`

- Stop the currently running gitweb server:

`git instaweb --stop`

- Restart the currently running gitweb server:

`git instaweb --restart`

