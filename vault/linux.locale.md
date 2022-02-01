---
id: linux.locale
title: Locale
desc: ''
updated: 1642441815101
created: 1642441815101
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# locale

> Get locale-specific information.
> More information: <https://manned.org/locale>.

- List all global environment variables describing the user's locale:

`locale`

- List all available locales:

`locale --all-locales`

- Display all available locales and the associated metadata:

`locale --all-locales --verbose`

- Display the current date format:

`locale date_fmt`

