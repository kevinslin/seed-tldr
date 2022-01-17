---
id: linux.genkernel
title: Genkernel
desc: ''
updated: 1642441815096
created: 1642441815096
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# genkernel

> Gentoo Linux utility to compile and install kernels.
> More information: <https://wiki.gentoo.org/wiki/Genkernel>.

- Automatically compile and install a generic kernel:

`sudo genkernel all`

- Build and install the bzImage|initramfs|kernel|ramdisk only:

`sudo genkernel {{bzImage|initramfs|kernel|ramdisk}}`

- Apply changes to the kernel configuration before compiling and installing:

`sudo genkernel --menuconfig all`

- Generate a kernel with a custom name:

`sudo genkernel --kernname={{custom_name}} all`

- Use a kernel source outside the default directory `/usr/src/linux`:

`sudo genkernel --kerneldir={{path/to/directory}} all`

