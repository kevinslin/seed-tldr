---
id: linux.distrobox-create
title: Distrobox Create
desc: ''
updated: 1642882717682
created: 1642882717682
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# distrobox-create

> Create Distrobox containers with an input name and image.
> The created container will be tightly integrated with the host, allowing sharing of the HOME directory of the user, external storage, external usb devices and graphical apps (X11/Wayland), and audio.
> More information: <https://distrobox.privatedns.org>.

- Create a distrobox using the Alpine image:

`distrobox-create {{container_name}} --image alpine`

- Clone a distrobox:

`distrobox-create --clone {{container_name}} {{cloned_container_name}}`

