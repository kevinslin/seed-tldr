---
id: common.doctl-compute-droplet
title: Doctl Compute Droplet
desc: ''
updated: 1642441815010
created: 1642441815010
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# doctl compute droplet

> List, create, and delete virtual machines which are called droplets.
> More information: <https://docs.digitalocean.com/reference/doctl/reference/compute/droplet/>.

- Create a droplet:

`doctl compute droplet create --region {{region}} --image {{os_image}} --size {{vps_type}} {{droplet_name}}`

- Delete a droplet:

`doctl compute droplet delete {{droplet_id|droplet_name}}`

- List droplets:

`doctl compute droplet list`

