---
id: osx.route
title: Route
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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

