---
id: common.rails-destroy
title: Rails Destroy
desc: ''
updated: 1623965306207
created: 1623965306207
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rails destroy

> Destroy Rails resources.
> More information: <https://guides.rubyonrails.org/command_line.html#bin-rails-destroy>.

- List all available generators to destroy:

`rails destroy`

- Destroy a model named Post:

`rails destroy model {{Post}}`

- Destroy a controller named Posts:

`rails destroy controller {{Posts}}`

- Destroy a migration that creates Posts:

`rails destroy migration {{CreatePosts}}`

- Destroy a scaffold for a model named Post:

`rails destroy scaffold {{Post}}`

