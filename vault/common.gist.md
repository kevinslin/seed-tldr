---
id: common.gist
title: Gist
desc: ''
updated: 1623965306186
created: 1623965306186
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gist

> Upload code to <https://gist.github.com.>
> More information: <https://github.com/defunkt/gist>.

- Log in in gist on this computer:

`gist --login`

- Create a gist from any number of text files:

`gist {{file.txt}} {{file2.txt}}`

- Create a private gist with a description:

`gist --private --description "{{A meaningful description}}" {{file.txt}} `

- Read contents from stdin and create a gist from it:

`{{echo "hello world"}} | gist`

- List your public and private gists:

`gist --list`

- List all public gists for any user:

`gist --list {{username}}`

- Update a gist using the id from URL:

`gist --update {{GIST_ID}} {{file.txt}}`

