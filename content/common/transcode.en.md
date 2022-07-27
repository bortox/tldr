---
author: ['Waldir Pimenta', 'Ruben Vereecken', '85pando', 'Agniva De Sarker', 'Sadeed', 'Seth Falco']
date: 1656325392
title: "transcode, TLDR Pages"
description: "transcode, Transcode video and audio codecs, and convert between media formats."
categories: "common"
---
> More information: <https://manned.org/transcode>.

- Create stabilization file to be able to remove camera shakes:

```bash
transcode -J stabilize -i input_file
```

- Remove camera shakes after creating stabilization file, transform video using XviD:

```bash
transcode -J transform -i input_file -y xvid -o output_file
```

- Resize the video to 640x480 pixels and convert to MPEG4 codec using XviD:

```bash
transcode -Z 640x480 -i input_file -y xvid -o output_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Sadeed](mailto:sadeeedw@gmail.com) | task, telnet, tldrl, tput, traceroute, transcode, type: add link (#7038) | 2021-10-23T20:45:06 | [81dc4a1e8016](https://github.com/tldr-pages/tldr/commit/81dc4a1e8016c5621134ebf80724be7d7d67c56a)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix descriptions split by mistake in #633 (#1098) | 2016-10-12T17:58:04 | [c15d705d4007](https://github.com/tldr-pages/tldr/commit/c15d705d4007cc9adfa737a0ec6b88bef56656a8)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[85pando](mailto:85pando@users.noreply.github.com) | Update transcode.md | 2015-11-11T13:08:08 | [cb1c42d1e43e](https://github.com/tldr-pages/tldr/commit/cb1c42d1e43e37ef20604be6b2684553c17b3d49)
[85pando](mailto:85pando@users.noreply.github.com) | Update transcode.md Sorry for long delay. After this discussion this is probably the best that is possible. | 2015-11-11T09:03:29 | [191b855355df](https://github.com/tldr-pages/tldr/commit/191b855355df45279b097c92f1974451c8a3f515)
[85pando](mailto:85pando@googlemail.com) | Fix: multiple one-lines I hope this is a valid solution for the problem of the long description. The solution is similar to the [...] | 2015-10-24T18:19:11 | [7d5449e69d0c](https://github.com/tldr-pages/tldr/commit/7d5449e69d0ce459955a5b6da13d85a72bfac4c8)
[85pando](mailto:85pando@googlemail.com) | Improve transcode: description | 2015-10-21T13:13:29 | [98c517519319](https://github.com/tldr-pages/tldr/commit/98c517519319aaf115a252e83e4ef60b5c951ba0)
[85pando](mailto:85pando@googlemail.com) | Fix transcode, better description, split commands | 2015-10-21T12:24:21 | [8b60691580c7](https://github.com/tldr-pages/tldr/commit/8b60691580c712e893b5e4c34f05e64b7c9c42d4)
[85pando](mailto:85pando@googlemail.com) | Add transcode transcode is a video stream editor. | 2015-10-21T11:44:14 | [79552ed44039](https://github.com/tldr-pages/tldr/commit/79552ed440398299189504df302bc778bac90c0a)

