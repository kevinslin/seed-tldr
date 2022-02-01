---
id: osx.spctl
title: Spctl
desc: ''
updated: 1642441815123
created: 1642441815123
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# spctl

> Manage the security assessment policy subsystem.
> Utility for managing Gatekeeper in macOS.
> More information: <https://www.unix.com/man-page/osx/8/SPCTL/>.

- Turn off Gatekeeper:

`spctl --master-disable`

- Add a rule to allow an application to run (labeling of rule is optional):

`spctl --add --label "{{rule_name}}" {{path/to/file}}`

- Turn on Gatekeeper:

`spctl --master-enable`

- List all rules on the system:

`spctl --list`

