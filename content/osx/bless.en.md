---
author: ['Axel Navarro', 'bl-ue', 'Emily Grace Seville', 'Shashwat']
date: 1644837703
title: "bless"
description: "bless, Set volume boot capability and startup disk options."
categories: "osx"
---
> More information: <https://ss64.com/osx/bless.html>.

- Bless a volume with only Mac OS X or Darwin, and create the BootX and `boot.efi` files as needed:

```bash
bless --folder /Volumes/Mac OS X/System/Library/CoreServices --bootinfo --bootefi
```

- Set a volume containing either Mac OS 9 and Mac OS X to be the active volume:

```bash
bless --mount /Volumes/Mac OS --setBoot
```

- Set the system to NetBoot and broadcast for an available server:

```bash
bless --netboot --server bsdp://255.255.255.255
```

- Gather information about the currently selected volume (as determined by the firmware), suitable for piping to a program capable of parsing Property Lists:

```bash
bless --info --plist
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Axel Navarro](mailto:navarroaxel@gmail.com) | bless: add more info link and fix examples (#5277) | 2021-03-08T20:08:37 | [fbe706f00b17](https://github.com/tldr-pages/tldr/commit/fbe706f00b1733000b041f48d51e3a38cb769f91)
[Shashwat](mailto:shashwatmahar12@gmail.com) | bless: add page (#4439) | 2020-10-07T13:39:23 | [f3b038020f64](https://github.com/tldr-pages/tldr/commit/f3b038020f640ae4ef7a0bf5dcbc6310ab0b6e15)

