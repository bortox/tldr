---
author: ['Nagiza', 'Waldir Pimenta', 'derNiklaas', 'Felix Yan']
date: 1633404950
title: "wodim"
description: "wodim, Command (aliased as `cdrecord` on some systems) for recording data to CDs or DVDs."
categories: "linux"
---
> Some invocations of wodim can cause destructive actions, such as erasing all the data on a disc.

> More information: <https://manned.org/wodim>.

- Display optical drives available to `wodim`:

```bash
wodim --devices
```

- Record ("burn") an audio-only disc:

```bash
wodim dev=/dev/optical_drive -audio track*.cdaudio
```

- Burn a file to a disc, ejecting the disc once done (some recorders require this):

```bash
wodim -eject dev=/dev/optical_drive -data file.iso
```

- Burn a file to the disc in an optical drive, potentially writing to multiple discs in succession:

```bash
wodim -tao dev=/dev/optical_drive -data file.iso
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Update wodim.md | 2017-09-07T05:55:01 | [627d2a650d34](https://github.com/tldr-pages/tldr/commit/627d2a650d3477add556c5c55a666f6974e4383e)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | wodim: shorten main desc; clarify "burn" vs record | 2017-09-07T05:55:01 | [1f06f4571cf4](https://github.com/tldr-pages/tldr/commit/1f06f4571cf495febfdf7e521f29d78e5092942b)
[Felix Yan](mailto:felixonmars@archlinux.org) | Fix a typo in pages/linux/wodim.md | 2017-08-04T21:58:04 | [e5e2945dfe89](https://github.com/tldr-pages/tldr/commit/e5e2945dfe89b8cdc9cd8df32378d0d92ad167f2)
[Nagiza](mailto:Nagiza@users.noreply.github.com) | wodim: add page (#1429) | 2017-07-25T20:50:58 | [2c5a7a4fde0f](https://github.com/tldr-pages/tldr/commit/2c5a7a4fde0fbbe1fd65846f36e5957f7fc74f6e)

