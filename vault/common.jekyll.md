---
id: common.jekyll
title: Jekyll
desc: ''
updated: 1615663978720
created: 1615663978720
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# jekyll

> A simple, blog-aware, static site generator.
> More information: <https://jekyllrb.com>.

- Generate a development server that will run at http&#x3A;//localhost:4000/:

`jekyll serve`

- Enable incremental regeneration:

`jekyll serve --incremental`

- Enable verbose output:

`jekyll serve --verbose`

- Generate the current directory into `./_site`:

`jekyll build`

- Clean the site (removes site output and `cache` directory) without building:

`jekyll clean`

