---
id: common.drush
title: Drush
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
# drush

> A command-line shell and scripting interface for Drupal.
> More information: <https://www.drush.org>.

- Enable module "foo":

`drush en {{foo}}`

- Uninstall module "foo":

`drush pmu {{foo}}`

- Clear all caches:

`drush cr`

- Clear CSS and JavaScript caches:

`drush cc css-js`

