---
id: linux.rusnapshot
title: Rusnapshot
desc: ''
updated: 1642441815112
created: 1642441815112
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rusnapshot

> BTRFS snapshotting utility written in Rust.
> More information: <https://github.com/Edu4rdSHL/rusnapshot>.

- Create a snapshot using a config file:

`sudo rusnapshot --config {{path/to/config.toml}} --cr`

- List created snapshots:

`sudo rusnapshot -c {{path/to/config.toml}} --list`

- Delete a snapshot by ID or the name of the snapshot:

`sudo rusnapshot -c {{path/to/config.toml}} --del --id {{snapshot_id}}`

- Delete all `hourly` snapshots:

`sudo rusnapshot -c {{path/to/config.toml}} --list --keep {{0}} --clean --kind {{hourly}}`

- Create a read-write snapshot:

`sudo rusnapshot -c {{path/to/config.toml}} --cr --rw`

- Restore a snapshot:

`sudo rusnapshot -c {{path/to/config.toml}} --id {{snapshot_id}} --restore`

