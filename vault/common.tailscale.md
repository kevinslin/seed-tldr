---
id: common.tailscale
title: Tailscale
desc: ''
updated: 1642441815074
created: 1642441815074
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tailscale

> A private WireGuard network service.
> Some subcommands such as `tailscale up` have their own usage documentation.
> More information: <https://tailscale.com>.

- Connect to Tailscale:

`sudo tailscale up`

- Disconnect from Tailscale:

`sudo tailscale down`

- Display the current Tailscale IP addresses:

`tailscale ip`

- Ping a peer node at the Tailscale layer and display which route it took for each response:

`tailscale ping {{ip|hostname}}`

- Analyze the local network conditions and display the result:

`tailscale netcheck`

- Start a web server for controlling Tailscale:

`tailscale web`

- Display a shareable identifier to help diagnose issues:

`tailscale bugreport`

- Display help for a subcommand:

`tailscale {{subcommand}} --help`

