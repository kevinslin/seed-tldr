---
id: common.stormlock
title: Stormlock
desc: ''
updated: 1642441815073
created: 1642441815073
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# Stormlock

> Centralized locking system.
> More information: <https://github.com/tmccombs/stormlock>.

- Acquire a lease for resource:

`stormlock aquire {{resource}}`

- Release the given lease for the given resource:

`stormlock release {{resource}} {{lease_id}}`

- Show information on the current lease for a resource, if any:

`stormlock current {{resource}}`

- Test if a lease for given resource is currently active:

`stormlock is-held {{resource}} {{lease_id}}`

