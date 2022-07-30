---
author: ['Starbeamrainbowlabs', 'Emily Grace Seville', 'Seth Falco']
date: 1647882468
title: "pasuspender"
description: "pasuspender, Temporarily suspends `pulseaudio` while another command is running to allow access to alsa."
categories: "linux"
---
> More information: <https://manned.org/pasuspender>.

- Suspend PulseAudio while running `jackd`:

```bash
pasuspender -- jackd -d alsa --device hw:0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Update pasuspender.md | 2017-11-25T11:15:44 | [d681bb4cb5c7](https://github.com/tldr-pages/tldr/commit/d681bb4cb5c7fcedb5658f923f4e00e4d878202c)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Update pasuspender.md | 2017-11-25T11:15:44 | [47003f70f5e8](https://github.com/tldr-pages/tldr/commit/47003f70f5e8049c4e0c22e33a70f3fd13ef1b7a)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | pasuspender: add page | 2017-11-25T11:15:44 | [5a60527de388](https://github.com/tldr-pages/tldr/commit/5a60527de388c8cc08af226fd6f737566edf921f)

