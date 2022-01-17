---
id: common.dokku
title: Dokku
desc: ''
updated: 1642441815010
created: 1642441815010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# dokku

> Docker powered mini-Heroku (PaaS).
> Easily deploy multiple apps to your server in different languages using a single `git-push` command.
> More information: <https://github.com/dokku/dokku>.

- List running apps:

`dokku apps`

- Create an app:

`dokku apps:create {{app_name}}`

- Remove an app:

`dokku apps:destroy {{app_name}}`

- Install plugin:

`dokku plugin:install {{full_repo_url}}`

- Link database to an app:

`dokku {{db}}:link {{db_name}} {{app_name}}`

