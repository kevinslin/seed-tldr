---
id: common.fdroidcl
title: Fdroidcl
desc: ''
updated: 1642441815017
created: 1642441815017
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fdroidcl

> F-Droid CLI client.
> More information: <https://github.com/mvdan/fdroidcl>.

- Fetch the F-Droid index:

`fdroidcl update`

- Display info about an app:

`fdroidcl show {{app_id}}`

- Download an APK file:

`fdroidcl download {{app_id}}`

- Search for an app in the index:

`fdroidcl search {{search_pattern}}`

- Install an app on a connected device:

`fdroidcl install {{app_id}}`

