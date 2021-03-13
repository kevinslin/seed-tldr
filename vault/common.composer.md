---
id: common.composer
title: Composer
desc: ''
updated: 1615655543048
created: 1615655543048
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

