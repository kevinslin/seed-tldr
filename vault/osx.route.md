---
id: osx.route
title: Route
desc: ''
updated: 1623965306235
created: 1623965306235
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# route

> Manually manipulate the routing tables.
> Necessitates to be root.

- Add a route to a destination through a gateway:

`sudo route add {{dest_ip_address}} {{gateway_address}}`

- Add a route to a /24 subnet through a gateway:

`sudo route add {{subnet_ip_address}}/24 {{gateway_address}}`

- Run in test mode (does not do anything, just print):

`sudo route -t add {{dest_ip_address}}/24 {{gateway_address}}`

- Remove all routes:

`sudo route flush`

- Delete a specific route:

`sudo route delete {{dest_ip_address}}/24`

- Lookup and display the route for a destination (hostname or IP address):

`sudo route get {{destination}}`

