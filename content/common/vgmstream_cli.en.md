---
author: ['Peder Bergebakken Sundt']
date: 1659299761
title: "vgmstream_cli"
description: "vgmstream_cli, Play a wide variety of audio formats used in video games and convert them into `wav`."
categories: "common"
---
> More information: <https://vgmstream.org/doc/USAGE>.

- Decode an `adc` file to `wav`. (Default output name is `input.wav`):

```bash
vgmstream_cli path/to/input.adc -o path/to/output.wav
```

- Print metadata without decoding the audio:

```bash
vgmstream_cli path/to/input.adc -m
```

- Decode an audio file without loops:

```bash
vgmstream_cli path/to/input.adc -o path/to/output.wav -i
```

- Decode with three loops, then add a 3s delay followed by a 5s fadeout:

```bash
vgmstream_cli path/to/input.adc -o path/to/output.wav -l 3.0 -f 5.0 -d 3.0
```

- Convert multiple files to `bgm_(original name).wav` (Default `-o` pattern is `?f.wav`):

```bash
vgmstream_cli -o path/to/bgm_?f.wav path/to/file1.adc path/to/file2.adc
```

- Play the file looping endlessly (`channels` and `rate` must match metadata):

```bash
vgmstream_cli path/to/input.adc -pec | aplay --format cd --channels 1 --rate 44100
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Peder Bergebakken Sundt](mailto:pbsds@hotmail.com) | vgmstream_cli: add page (#7956) | 2022-07-31T22:36:01 | [687415d81c56](https://github.com/tldr-pages/tldr/commit/687415d81c56bd49ca670dbb71d6d99c7033dc92)

