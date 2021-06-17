---
id: common.linkchecker
title: Linkchecker
desc: ''
updated: 1623965306195
created: 1623965306195
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# linkchecker

> Command-line client to check HTML documents and websites for broken links.
> More information: <https://linkchecker.github.io/linkchecker/>.

- Find broken links on <https://example.com/>:

`linkchecker {{https://example.com/}}`

- Also check URLs that point to external domains:

`linkchecker --check-extern {{https://example.com/}}`

- Ignore URLs that match a specific regular expression:

`linkchecker --ignore-url {{regular_expression}} {{https://example.com/}}`

- Output results to a CSV file:

`linkchecker --file-output {{csv}}/{{path/to/file}} {{https://example.com/}}`

