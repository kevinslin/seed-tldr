---
id: common.linkchecker
title: Linkchecker
desc: ''
updated: 1615655543067
created: 1615655543067
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# linkchecker

> Command line client to check HTML documents and websites for broken links.
> More information: <https://linkchecker.github.io/linkchecker/>.

- Find broken links on <https://example.com/>:

`linkchecker {{https://example.com/}}`

- Also check URLs that point to external domains:

`linkchecker --check-extern {{https://example.com/}}`

- Ignore URLs that match a specific regex:

`linkchecker --ignore-url {{regex}} {{https://example.com/}}`

- Output results to a CSV file:

`linkchecker --file-output {{csv}}/{{path/to/file}} {{https://example.com/}}`

