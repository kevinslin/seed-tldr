---
id: linux.bpftool
title: Bpftool
desc: ''
updated: 1642441815089
created: 1642441815089
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# bpftool

> Tool for inspection and simple manipulation of eBPF programs and maps.
> Some subcommands such as `bpftool prog` have their own usage documentation.
> More information: <https://manned.org/bpftool>.

- List information about loaded `eBPF` programs:

`bpftool prog list`

- List `eBPF` program attachments in the kernel networking subsystem:

`bpftool net list`

- List all active links:

`bpftool link list`

- List all `raw_tracepoint`, `tracepoint`, `kprobe` attachments in the system:

`bpftool perf list`

- List `BPF Type Format (BTF)` data:

`bpftool btf list`

- List information about loaded maps:

`bpftool map list`

- Probe a network device "eth0" for supported `eBPF` features:

`bpftool feature probe dev {{eth0}}`

- Run commands in batch mode from a file:

`bpftool batch file {{myfile}}`

