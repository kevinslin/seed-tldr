---
id: common.kiwi-ng
title: Kiwi Ng
desc: ''
updated: 1642441815039
created: 1642441815039
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# kiwi-ng

> KIWI NG is an OS image and appliance builder.
> More information: <https://osinside.github.io/kiwi/>.

- Build an appliance:

`kiwi-ng system build --description={{path/to/directory}} --target-dir={{path/to/directory}}`

- Show build result of built appliance:

`kiwi-ng result list --target-dir={{path/to/directory}}`

- Display help:

`kiwi-ng help`

- Display version:

`kiwi-ng -v`

