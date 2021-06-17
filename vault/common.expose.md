---
id: common.expose
title: Expose
desc: ''
updated: 1623965306183
created: 1623965306183
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# expose

> An open source tunnel application for sharing websites.
> More information: <https://beyondco.de/docs/expose>.

- Register your authentication token:

`expose token {{token}}`

- Share the current working directory:

`expose`

- Share the current working directory with a specific subdomain:

`expose --subdomain={{subdomain}}`

- Share a local URL:

`expose share {{url}}`

- Run the Expose server:

`expose serve`

- Run the Expose server with a specific hostname:

`expose serve {{hostname}}`

