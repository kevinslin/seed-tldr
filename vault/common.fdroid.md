---
id: common.fdroid
title: Fdroid
desc: ''
updated: 1623965306184
created: 1623965306184
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fdroid

> F-Droid build tool.
> F-Droid is an installable catalog of FOSS (Free and Open Source Software) applications for the Android platform.
> More information: <https://f-droid.org/>.

- Build a specific app:

`fdroid build {{app_id}}`

- Build a specific app in a build server VM:

`fdroid build {{app_id}} --server`

- Publish the app to the local repository:

`fdroid publish {{app_id}}`

- Install the app on every connected device:

`fdroid install {{app_id}}`

- Check if the metadata is formatted correctly:

`fdroid lint --format {{app_id}}`

- Fix the formatting automatically (if possible):

`fdroid rewritemeta {{app_id}}`

