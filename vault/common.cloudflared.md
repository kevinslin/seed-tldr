---
id: common.cloudflared
title: Cloudflared
desc: ''
updated: 1623965016116
created: 1623965016116
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# cloudflared

> Command-line tool to create a persistent connection to the Cloudflare network.
> More information: <https://developers.cloudflare.com/argo-tunnel/>.

- Authenticate and associate the connection to a domain in the Cloudflare account:

`cloudflared tunnel login`

- Establish a tunnel to a host in Cloudflare from the local server:

`cloudflared tunnel --hostname {{hostname}} localhost:{{port_number}}`

- Establish a tunnel to a host in Cloudflare from the local server, without verifying the local server's certificate:

`cloudflared tunnel --hostname {{hostname}} localhost:{{port_number}} --no-tls-verify`

- Save logs to a file:

`cloudflared tunnel --hostname {{hostname}} http://localhost:{{port_number}} --loglevel {{panic|fatal|error|warn|info|debug}} --logfile {{path/to/file}}`

- Install cloudflared as a system service:

`cloudflared service install`

