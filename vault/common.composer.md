---
id: common.composer
title: Composer
desc: ''
updated: 1623965306177
created: 1623965306177
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# composer

> A package-based dependency manager for PHP projects.
> More information: <https://getcomposer.org/>.

- Interactively create a `composer.json` file:

`composer init`

- Add a package as a dependency for this project, adding it to `composer.json`:

`composer require {{user/package_name}}`

- Install all the dependencies in this project's `composer.json` and create `composer.lock`:

`composer install`

- Uninstall a package from this project, removing it as a dependency from `composer.json`:

`composer remove {{user/package_name}}`

- Update all the dependencies in this project's `composer.json` and note versions in `composer.lock` file:

`composer update`

- Update composer lock only after updating `composer.json` manually:

`composer update --lock`

- Learn more about why a dependency can't be installed:

`composer why-not {{user/package_name}}`

- Update composer to its latest version:

`composer self-update`

