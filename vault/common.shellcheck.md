---
id: common.shellcheck
title: Shellcheck
desc: ''
updated: 1615663978734
created: 1615663978734
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# shellcheck

> Shell script static analysis tool.
> More information: <https://www.shellcheck.net/>.

- Check a shell script:

`shellcheck {{file.sh}}`

- Override script's shebang:

`shellcheck --shell {{sh|bash|ksh}} {{file.sh}}`

- Ignore certain errors:

`shellcheck --exclude {{SC1009}} {{file.sh}}`

- Ignore multiple errors:

`shellcheck --exclude {{SC1009,SC1073}} {{file.sh}}`

