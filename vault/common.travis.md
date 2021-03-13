---
id: common.travis
title: Travis
desc: ''
updated: 1615655543090
created: 1615655543090
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# travis

> Command line client to interface with Travis CI.
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

