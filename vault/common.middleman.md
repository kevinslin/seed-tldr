---
id: common.middleman
title: Middleman
desc: ''
updated: 1615655543069
created: 1615655543069
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# middleman

> Static site generator written in Ruby.
> More information: <https://middlemanapp.com/>.

- Create a new Middleman project:

`middleman init "{{project_name}}"`

- Start local server for current project on port 4567:

`middleman server`

- Start local server for current project on a specified port:

`middleman server -p "{{port}}"`

- Build the project in the current directory to prepare for deployment:

`bundle exec middleman build`

- Deploy the Middleman project in the current directory:

`middleman deploy`

