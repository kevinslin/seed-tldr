---
id: common.heroku
title: Heroku
desc: ''
updated: 1615655543062
created: 1615655543062
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# heroku

> Create and manage Heroku apps from the command line.
> More information: <https://www.heroku.com/>.

- Login to your heroku account:

`heroku login`

- Create a heroku app:

`heroku create`

- Show logs for an app:

`heroku logs --app {{app_name}}`

- Run a one-off process inside a dyno (Heroku virtual machine):

`heroku run {{process_name}} --app {{app_name}}`

- List dynos (Heroku virtual machines) for an app:

`heroku ps --app {{app_name}}`

- Permanently destroy an app:

`heroku destroy --app {{app_name}}`

