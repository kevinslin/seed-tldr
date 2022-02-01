---
id: common.travis
title: Travis
desc: ''
updated: 1642441815077
created: 1642441815077
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# travis

> Command-line client to interface with Travis CI.
> More information: <https://github.com/travis-ci/travis.rb>.

- Display the client version:

`travis version`

- Authenticate the CLI client against the server, using an authentication token:

`travis login`

- List repositories the user has permissions on:

`travis repos`

- Encrypt values in `.travis.yml`:

`travis encrypt {{token}}`

- Generate a `.travis.yml` file and enable the project:

`travis init`

