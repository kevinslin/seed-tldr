---
id: common.monodis
title: Monodis
desc: ''
updated: 1642441815048
created: 1642441815048
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# monodis

> The Mono Common Intermediate Language (CIL) disassembler.
> More information: <https://www.mono-project.com/docs/tools+libraries/tools/monodis/>.

- Disassemble an assembly to textual CIL:

`monodis {{path/to/assembly.exe}}`

- Save the output to a file:

`monodis --output={{path/to/output.il}} {{path/to/assembly.exe}}`

- Show information about an assembly:

`monodis --assembly {{path/to/assembly.dll}}`

- List the references of an assembly:

`monodis --assemblyref {{path/to/assembly.exe}}`

- List all the methods in an assembly:

`monodis --method {{path/to/assembly.exe}}`

- Show a list of resources embedded within an assembly:

`monodis --manifest {{path/to/assembly.dll}}`

- Extract all the embedded resources to the current directory:

`monodis --mresources {{path/to/assembly.dll}}`

