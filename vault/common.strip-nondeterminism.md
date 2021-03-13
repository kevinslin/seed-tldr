---
id: common.strip-nondeterminism
title: Strip Nondeterminism
desc: ''
updated: 1615655543087
created: 1615655543087
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# strip-nondeterminism

> A tool to remove non-deterministic information (e.g. timestamps) from files.
> More information: <https://salsa.debian.org/reproducible-builds/strip-nondeterminism>.

- Strip nondeterministic information from a file:

`strip-nondeterminism {{path/to/file}}`

- Strip nondeterministic information from a file manually specifying the filetype:

`strip-nondeterminism --type {{filetype}} {{path/to/file}}`

- Strip nondeterministic information from a file; instead of removing timestamps set them to the specified UNIX timestamp:

`strip-nondeterminism --timestamp {{unix_timestamp}} {{path/to/file}}`

