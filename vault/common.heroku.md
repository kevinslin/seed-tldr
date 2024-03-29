---
id: common.heroku
title: Heroku
desc: ''
updated: 1642441815032
created: 1642441815032
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# heroku

> Create and manage Heroku apps from the command-line.
> More information: <https://www.heroku.com/>.

- Log in to your Heroku account:

`heroku login`

- Create a Heroku app:

`heroku create`

- Show logs for an app:

`heroku logs --app {{app_name}}`

- Run a one-off process inside a dyno (Heroku virtual machine):

`heroku run {{process_name}} --app {{app_name}}`

- List dynos (Heroku virtual machines) for an app:

`heroku ps --app {{app_name}}`

- Permanently destroy an app:

`heroku destroy --app {{app_name}}`

