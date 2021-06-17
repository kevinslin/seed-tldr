---
id: common.wp
title: Wp
desc: ''
updated: 1623965016155
created: 1623965016155
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wp

> The official command-line interface to manage WordPress instances.
> More information: <https://wp-cli.org/>.

- Print information about the operating system, shell, PHP, and WP-CLI (`wp`) installation:

`wp --info`

- Update WP-CLI:

`wp cli update`

- Install and activate a WordPress plugin:

`wp plugin install {{plugin}} --activate`

- Replace all instances of a string in the database:

`wp search-replace {{old_string}} {{new_string}}`

- Import the contents of a WordPress Extended RSS (WXR) file:

`wp import {{path/to/file.xml}}`

