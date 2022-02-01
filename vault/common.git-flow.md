---
id: common.git-flow
title: Git Flow
desc: ''
updated: 1642441815024
created: 1642441815024
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git flow

> A collection of Git extensions to provide high-level repository operations.
> More information: <https://github.com/nvie/gitflow>.

- Initialize it inside an existing Git repository:

`git flow init`

- Start developing on a feature branch based on `develop`:

`git flow feature start {{feature}}`

- Finish development on a feature branch, merging it into the `develop` branch and deleting it:

`git flow feature finish {{feature}}`

- Publish a feature to the remote server:

`git flow feature publish {{feature}}`

- Get a feature published by another user:

`git flow feature pull origin {{feature}}`

