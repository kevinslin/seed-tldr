---
id: common.gitlab-ctl
title: GitLab Ctl
desc: ''
updated: 1623965016129
created: 1623965016129
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gitlab-ctl

> CLI tool for managing the GitLab omnibus.
> More information: <https://docs.gitlab.com/omnibus/maintenance/>.

- Display the status of every service:

`sudo gitlab-ctl status`

- Display the status of a specific service:

`sudo gitlab-ctl status {{nginx}}`

- Restart every service:

`sudo gitlab-ctl restart`

- Restart a specific service:

`sudo gitlab-ctl restart {{nginx}}`

- Display the logs of every service and keep reading until `Ctrl + C` is pressed:

`sudo gitlab-ctl tail`

- Display the logs of a specific service:

`sudo gitlab-ctl tail {{nginx}}`

