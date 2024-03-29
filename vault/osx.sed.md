---
id: osx.sed
title: Sed
desc: ''
updated: 1642441815122
created: 1642441815122
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# sed

> Edit text in a scriptable manner.
> More information: <https://ss64.com/osx/sed.html>.

- Replace the first occurrence of a string in a file, and print the result:

`sed 's/{{find}}/{{replace}}/' {{filename}}`

- Replace all occurrences of an extended regular expression in a file:

`sed -E 's/{{regular_expression}}/{{replace}}/g' {{filename}}`

- Replace all occurrences of a string [i]n a file, overwriting the file (i.e. in-place):

`sed -i '' 's/{{find}}/{{replace}}/g' {{filename}}`

- Replace only on lines matching the line pattern:

`sed '/{{line_pattern}}/s/{{find}}/{{replace}}/' {{filename}}`

- Print only text between n-th line till the next empty line:

`sed -n '{{line_number}},/^$/p' {{filename}}`

- Apply multiple find-replace expressions to a file:

`sed -e 's/{{find}}/{{replace}}/' -e 's/{{find}}/{{replace}}/' {{filename}}`

- Replace separator `/` by any other character not used in the find or replace patterns, e.g. `#`:

`sed 's#{{find}}#{{replace}}#' {{filename}}`

- [d]elete the line at the specific line number [i]n a file, overwriting the file:

`sed -i '' '{{line_number}}d' {{filename}}`

