---
id: common.drupal
title: Drupal
desc: ''
updated: 1642441815011
created: 1642441815011
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# drupal

> Generate boilerplate code, interact with and debug Drupal projects.
> Some subcommands such as `drupal check` have their own usage documentation.
> More information: <https://drupalconsole.com/>.

- Install a module:

`drupal module:install {{module_name}}`

- Uninstall a module:

`drupal module:uninstall {{module_name}}`

- Clear all caches:

`drupal cache:rebuild`

- View current Drupal installation status:

`drupal site:status`

