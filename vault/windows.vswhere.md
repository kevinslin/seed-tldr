---
id: windows.vswhere
title: Vswhere
desc: ''
updated: 1642441815130
created: 1642441815130
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# vswhere

> Locate Visual Studio 2017 and newer installations.
> More information: <https://github.com/microsoft/vswhere>.

- Find the path of vcvarsall.bat to set environment variables:

`vswhere -products * -latest -prerelease -find **/VC/Auxiliary/Build/vcvarsall.bat`

- Find the directory of the x64 MSVC compiler (cl.exe, etc):

`vswhere -products * -latest -prerelease -find **/Hostx64/x64/*`

- Find the directory of Clang bundled with Visual Studio bundled (clang-cl, clang-tidy, etc):

`vswhere -products * -latest -prerelease -find **/Llvm/bin/*`

- Find the path of `MSBuild.exe`:

`vswhere -products * -latest -prerelease -find MSBuild/**/Bin/MSBuild.exe`

