---
id: common.wrangler
title: Wrangler
desc: ''
updated: 1623965306216
created: 1623965306216
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wrangler

> Cloudflare Workers command-line tool.
> More information: <https://developers.cloudflare.com/workers/>.

- Initialize a project with a skeleton configuration:

`wrangler init {{project_name}}`

- Authenticate with Cloudflare:

`wrangler login`

- Start a local development server:

`wrangler dev --host {{hostname}}`

- Publish the worker script:

`wrangler publish`

- Aggregate logs from the production worker:

`wrangler tail`

