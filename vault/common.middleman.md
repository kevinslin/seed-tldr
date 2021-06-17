---
id: common.middleman
title: Middleman
desc: ''
updated: 1623965306196
created: 1623965306196
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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

