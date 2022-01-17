---
id: common.resume
title: Resume
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
# resume

> CLI tool to easily setup a new resume.
> More information: <https://github.com/jsonresume/resume-cli>.

- Create a new `resume.json` file in the current working directory:

`resume init`

- Validate a `resume.json` against schema tests to ensure it complies with the standard:

`resume validate`

- Export a resume locally in a stylized HTML or PDF format:

`resume export {{path/to/html_or_pdf}}`

- Start a web server that serves a local `resume.json`:

`resume serve`

