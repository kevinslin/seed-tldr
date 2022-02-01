---
id: common.smalltalkci
title: Smalltalkci
desc: ''
updated: 1642441815069
created: 1642441815069
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# smalltalkci

> Framework for testing Smalltalk projects with GitHub Actions, Travis CI, AppVeyor, GitLab CI, and others.
> More information: <https://github.com/hpi-swa/smalltalkCI>.

- Run tests for a configuration file:

`smalltalkci {{path/to/.smalltalk.ston}}`

- Run tests for the `.smalltalk.ston` configuration in the current directory:

`smalltalkci`

- Debug tests in headful mode (show VM window):

`smalltalkci --headful`

- Download and prepare a well-known smalltalk image for the tests:

`smalltalkci --smalltalk {{Squeak64-Trunk}}`

- Specify a custom Smalltalk image and VM:

`smalltalkci --image {{path/to/Smalltalk.image}} -- vm {{path/to/vm}}`

- Clean up caches and delete builds:

`smalltalkci --clean`

