---
id: common.traefik
title: Traefik
desc: ''
updated: 1615663978737
created: 1615663978737
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# traefik

> A HTTP reverse proxy and load balancer.
> More information: <https://traefik.io>.

- Start server with default config:

`traefik`

- Start server with a custom config file:

`traefik --c {{config_file}}.toml`

- Start server with cluster mode enabled:

`traefik --cluster`

- Start server with web UI enabled:

`traefik --web`

