---
id: linux.v4l2-ctl
title: V4l2 Ctl
desc: ''
updated: 1642441815116
created: 1642441815116
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# v4l2-ctl

> Control video devices.
> More information: <https://manned.org/v4l2-ctl>.

- List all video devices:

`v4l2-ctl --list-devices`

- List supported video formats and resolutions of default video device `/dev/video0`:

`v4l2-ctl --list-formats-ext`

- List supported video formats and resolutions of a specific video device:

`v4l2-ctl --list-formats-ext --device {{path/to/video_device}}`

- Get all details of a video device:

`v4l2-ctl --all --device {{path/to/video_device}}`

- Capture a JPEG photo with a specfic resolution from video device:

`v4l2-ctl --device {{path/to/video_device}} --set-fmt-video=width={{width}},height={{height}},pixelformat=MJPG --stream-mmap --stream-to={{path/to/output.jpg}} --stream-count=1`

- Capture a raw video stream from video device:

`v4l2-ctl --device {{path/to/video_device}} --set-fmt-video=width={{width}},height={{height}},pixelformat={{format}} --stream-mmap --stream-to={{path/to/output}} --stream-count={{number_of_frames_to_capture}}`

- List all video device's controls and their values:

`v4l2-ctl --list-ctrls --device {{/path/to/video_device}}`

