---
author: ['Anja Elzinger', 'Waldir Pimenta', 'Stig124', 'kalebo', 'Jacob Rosales Chase']
date: 1634201302
title: "beep"
description: "beep, A utility to beep the PC speaker."
categories: "linux"
---
> More information: <https://github.com/spkr-beep/beep>.

- Play a beep:

```bash
beep
```

- Play a beep that repeats:

```bash
beep -r repetitions
```

- Play a beep at a specified frequency (Hz) and duration (milliseconds):

```bash
beep -f frequency -l duration
```

- Play each new frequency and duration as a distinct beep:

```bash
beep -f frequency -l duration -n -f frequency -l duration
```

- Play the C major scale:

```bash
beep -f 262 -n -f 294 -n -f 330 -n -f 349 -n -f 392 -n -f 440 -n -f 494 -n -f 523
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anja Elzinger](mailto:35960947+entensee403@users.noreply.github.com) | beep: add German translation (#6939) | 2021-10-14T10:48:22 | [6c5fe7692586](https://github.com/tldr-pages/tldr/commit/6c5fe7692586c9913e3b490efffc5011764ccadc)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Jacob Rosales Chase](mailto:jxr450@case.edu) | beep: fix mismatched braces (#2553) | 2018-11-04T12:30:35 | [f10b0a11ab71](https://github.com/tldr-pages/tldr/commit/f10b0a11ab7117bcf8b97a0a34cf21168aacf970)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | beep: minor capitalization fixes | 2016-11-21T08:51:58 | [587abbcfae2c](https://github.com/tldr-pages/tldr/commit/587abbcfae2c2ca82a2b0d27aeb8f5abc943e887)
[kalebo](mailto:kaleb.olson@gmail.com) | beep: add page (#1145) | 2016-11-21T08:50:22 | [6877adf7c5d1](https://github.com/tldr-pages/tldr/commit/6877adf7c5d15e5a35370afe80e702a826b6dbe8)

