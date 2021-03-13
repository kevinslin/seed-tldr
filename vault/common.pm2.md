---
id: common.pm2
title: Pm2
desc: ''
updated: 1615663978730
created: 1615663978730
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pm2

> Process manager for Node.js.
> Used for log management, monitoring and configuring processes.
> More information: <https://pm2.keymetrics.io>.

- Start a process with a name that can be used for later operations:

`pm2 start {{app.js}} --name {{myapp}}`

- List processes:

`pm2 list`

- Monitor all processes:

`pm2 monit`

- Stop a process:

`pm2 stop {{myapp}}`

- Restart a process:

`pm2 restart {{myapp}}`

- Dump all processes for resurrecting them later:

`pm2 save`

- Resurrect previously dumped processes:

`pm2 resurrect`

- Launch monitoring:

`pm2 monit`

