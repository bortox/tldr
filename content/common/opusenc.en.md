---
author: ['Agno94']
date: 1603713532
title: "opusenc"
description: "opusenc, Convert WAV or FLAC audio to Opus."
categories: "common"
---
> More information: <https://opus-codec.org/docs/opus-tools/opusenc.html>.

- Convert WAV to Opus using default options:

```bash
opusenc path/to/input.wav path/to/output.opus
```

- Convert stereo audio at the highest quality level:

```bash
opusenc --bitrate 512 path/to/input.wav path/to/output.opus
```

- Convert 5.1 surround sound audio at the highest quality level:

```bash
opusenc --bitrate 1536 path/to/input.flac path/to/output.opus
```

- Convert speech audio at the lowest quality level:

```bash
opusenc path/to/input.wav --downmix-mono --bitrate 6 path/to/out.opus
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Agno94](mailto:agnophi@gmail.com) | opusenc: move from linux to common (#4860) | 2020-10-26T12:58:52 | [59dbe4e9ef5f](https://github.com/tldr-pages/tldr/commit/59dbe4e9ef5fd21d2e1b4eaea8da5ec3b0b0c588)

