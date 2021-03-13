---
id: common.roave-backward-compatibility-check
title: Roave Backward Compatibility Check
desc: ''
updated: 1615663978732
created: 1615663978732
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# roave-backward-compatibility-check

> A tool that can be used to verify backward compatibility breaks between two versions of a PHP library.
> More information: <https://github.com/Roave/BackwardCompatibilityCheck>.

- Check for breaking changes since the last tag:

`roave-backward-compatibility-check`

- Check for breaking changes since a specific tag:

`roave-backward-compatibility-check --from={{git_reference}}`

- Check for breaking changes between the last tag and a specific reference:

`roave-backward-compatibility-check --to={{git_reference}}`

- Check for breaking changes and output to Markdown:

`roave-backward-compatibility-check --format=markdown > {{results.md}}`

