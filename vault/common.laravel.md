---
id: common.laravel
title: Laravel
desc: ''
updated: 1623965306195
created: 1623965306195
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# laravel

> A command-line installer for the Laravel framework.
> More information: <https://laravel.com>.

- Create a new Laravel application:

`laravel new {{name}}`

- Use the latest development release:

`laravel new {{name}} --dev`

- Overwrite if the directory already exists:

`laravel new {{name}} --force`

- Install the Laravel Jetstream scaffolding:

`laravel new {{name}} --jet`

- Install the Laravel Jetstream scaffolding with a specific stack:

`laravel new {{name}} --jet --stack {{livewire|inertia}}`

- Install the Laravel Jetstream scaffolding with support for teams:

`laravel new {{name}} --jet --teams`

- List the available installer commands:

`laravel list`

