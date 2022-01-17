---
id: common.recsel
title: Recsel
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# recsel

> Print records from a recfile: a human-editable, plain text database.
> More information: <https://www.gnu.org/software/recutils/manual/recutils.html>.

- Extract name and version field:

`recsel -p name,version {{data.rec}}`

- Use "~" to match a string with a given regular expression:

`recsel -e "{{field_name}} ~ '{{regular_expression}}' {{data.rec}}"`

- Use a predicate to match a name and a version:

`recsel -e "name ~ '{{regular_expression}}' && version ~ '{{regular_expression}}'" {{data.rec}}`

