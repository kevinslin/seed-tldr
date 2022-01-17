---
id: linux.slapt-src
title: Slapt Src
desc: ''
updated: 1642441815113
created: 1642441815113
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# slapt-src

> A utility to automate building of slackbuilds.
> SlackBuild sources need to be configured in the slapt-srcrc file.
> More information: <https://github.com/jaos/slapt-src>.

- Update the list of available slackbuilds and versions:

`slapt-src --update`

- List all available slackbuilds:

`slapt-src --list`

- Fetch, build and install the specified slackbuild(s):

`slapt-src --install {{slackbuild_name}}`

- Locate slackbuilds by their name or description:

`slapt-src --search {{search_term}}`

- Display information about a slackbuild:

`slapt-src --show {{slackbuild_name}}`

