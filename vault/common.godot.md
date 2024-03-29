---
id: common.godot
title: Godot
desc: ''
updated: 1642441815030
created: 1642441815030
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# godot

> An open source 2D and 3D game engine.
> More information: <https://godotengine.org/>.

- Run a project if the current directory contains a `project.godot` file, otherwise open the project manager:

`godot`

- Edit a project (the current directory must contain a `project.godot` file):

`godot -e`

- Open the project manager even if the current directory contains a `project.godot` file:

`godot -p`

- Export a project for a given export preset (the preset must be defined in the project):

`godot --export {{preset}} {{output_path}}`

- Execute a standalone GDScript file (the script must inherit from `SceneTree` or `MainLoop`):

`godot -s {{script.gd}}`

