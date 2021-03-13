---
id: common.googler
title: Googler
desc: ''
updated: 1615655543061
created: 1615655543061
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# googler

> Search Google from command line.
> More information: <https://github.com/jarun/googler>.

- Search Google for a keyword:

`googler {{keyword}}`

- Search Google and open the first result in web browser:

`googler -j {{keyword}}`

- Show N search results (default 10):

`googler -n {{N}} {{keyword}}`

- Disable automatic spelling correction:

`googler -x {{keyword}}`

- Search one site for a keyword:

`googler -w {{site}} {{keyword}}`

- Show Google search result in JSON format:

`googler --json {{keyword}}`

- Perform in-place self-upgrade:

`googler -u`

- For more help in interactive mode:

`?`

