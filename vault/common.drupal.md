---
id: common.drupal
title: Drupal
desc: ''
updated: 1623965016122
created: 1623965016122
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# drupal

> CLI for Drupal.
> Generates boilerplate code, interacts with and debugs Drupal projects.
> More information: <https://drupalconsole.com/>.

- Install a module:

`drupal module:install {{module_name}}`

- Uninstall a module:

`drupal module:uninstall {{module_name}}`

- Clear all caches:

`drupal cache:rebuild`

- View current Drupal installation status:

`drupal site:status`

