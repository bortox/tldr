---
author: ['marchersimon']
date: 1615201064
title: "musescore, TLDR Pages"
description: "musescore, MuseScore 3 sheet music editor."
categories: "common"
---
> More information: <https://musescore.org/en/handbook/3/command-line-options>.

- Use a specific audio driver:

```bash
musescore --audio-driver jack|alsa|portaudio|pulse
```

- Set the MP3 output bitrate in kbit/s:

```bash
musescore --bitrate bitrate
```

- Start MuseScore in debug mode:

```bash
musescore --debug
```

- Enable experimental features, such as layers:

```bash
musescore --experimental
```

- Export the given file to the specified output file. The file type depends on the given extension:

```bash
musescore --export-to output_file input_file
```

- Print a diff between the given scores:

```bash
musescore --diff path/to/file1 path/to/file2
```

- Specify a MIDI import operations file:

```bash
musescore --midi-operations path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | musescore: add page (#5368) | 2021-03-08T11:57:44 | [7a3f7174af12](https://github.com/tldr-pages/tldr/commit/7a3f7174af123c5bc498d25d410361c362558a9d)

