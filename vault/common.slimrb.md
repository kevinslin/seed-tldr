---
id: common.slimrb
title: Slimrb
desc: ''
updated: 1643710045553
created: 1643710045553
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# slimrb

> Convert Slim files to HTML.
> More information: <https://rdoc.info/gems/slim/frames#slim-command-slimrb>.

- Convert a Slim file to HTML:

`slimrb {{input.slim}} {{output.html}}`

- Convert a Slim file and output to prettified HTML:

`slimrb --pretty {{input.slim}} {{output.html}}`

- Convert a Slim file to ERB:

`slimrb --erb {{input.slim}} {{output.erb}}`

