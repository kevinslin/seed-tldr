---
id: common.vercel
title: Vercel
desc: ''
updated: 1642441815079
created: 1642441815079
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vercel

> Deploy and manage your Vercel deployments.
> More information: <https://vercel.com/docs/cli>.

- Deploy the current directory:

`vercel`

- Deploy the current directory to production:

`vercel --prod`

- Deploy a directory:

`vercel {{path/to/project}}`

- Initialize an example project:

`vercel init`

- Deploy with Environment Variables:

`vercel --env {{ENV}}={{var}}`

- Build with Environment Variables:

`vercel --build-env {{ENV}}={{var}}`

- Set default regions to enable the deployment on:

`vercel --regions {{region_id}}`

- Remove a deployment:

`vercel remove {{project_name}}`

