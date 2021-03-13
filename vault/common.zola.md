---
id: common.zola
title: Zola
desc: ''
updated: 1615663978740
created: 1615663978740
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# zola

> A static site generator in a single binary with everything built-in.
> More information: <https://www.getzola.org/documentation/getting-started/cli-usage/>.

- Create the directory structure used by Zola at the given directory:

`zola init {{my_site}}`

- Build the whole site in the `public` directory after deleting it:

`zola build`

- Build the whole site into a different directory:

`zola build --output-dir {{path/to/output_directory/}}`

- Build and serve the site using a local server (default is `127.0.0.1:1111`):

`zola serve`

- Build all pages just like the build command would, but without writing any of the results to disk:

`zola check`

