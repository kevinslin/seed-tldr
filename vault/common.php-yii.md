---
id: common.php-yii
title: Php Yii
desc: ''
updated: 1615663978729
created: 1615663978729
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# php yii

> Yii Framework's command line interface.
> More information: <https://yiiframework.com>.

- Display a list of all available commands:

`php yii {{help}}`

- Start PHP's built-in web server for the current Yii application:

`php yii {{serve}}`

- Generate a controller, views and related files for the CRUD actions on the specified model class:

`php yii {{gii/crud}} --modelClass={{ModelName}} --controllerClass={{ControllerName}}`

