---
author: ['Waldir Pimenta', 'Felix Yan', 'Ruben Vereecken', 'Igor Shubovych', 'CleanMachine1', 'Dario Vladović', 'rprieto', 'marchersimon']
date: 1627149810
title: "uname, TLDR Pages"
description: "uname, Print details about the current machine and the operating system running on it."
categories: "common"
---
> See also `lsb_release`.

> More information: <https://www.gnu.org/software/coreutils/uname>.

- Print kernel name:

```bash
uname
```

- Print system architecture and processor information:

```bash
uname --machine --processor
```

- Print kernel name, kernel release and kernel version:

```bash
uname --kernel-name --kernel-release --kernel-version
```

- Print system hostname:

```bash
uname --nodename
```

- Print all available system information:

```bash
uname --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | uname: refresh (#6242) | 2021-07-24T20:03:30 | [a9547d01840a](https://github.com/tldr-pages/tldr/commit/a9547d01840a15915be643cc2ebf50a3f9035d67)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | uname: add more information link (#5633) | 2021-03-30T16:01:18 | [4f4592712cd8](https://github.com/tldr-pages/tldr/commit/4f4592712cd8655a7994d9d8d230c468b7bc8a38)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | uname: split page to provide contextually-relevant info in the main desc. (#1156) | 2016-11-19T18:41:17 | [cb277137b63a](https://github.com/tldr-pages/tldr/commit/cb277137b63aed1c4da6226be99f1e58905b8c08)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | uname -a | 2015-12-23T17:16:11 | [b38e272b47e1](https://github.com/tldr-pages/tldr/commit/b38e272b47e1bcf12232f2a78109d34210da4f89)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Fix linting | 2015-12-07T02:51:25 | [f3b5a63f0e3a](https://github.com/tldr-pages/tldr/commit/f3b5a63f0e3aa85745ba76b8236d99b0c513b284)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | mention lsb_release | 2015-10-09T09:54:24 | [c4ca2f9ea354](https://github.com/tldr-pages/tldr/commit/c4ca2f9ea3545811f9ba63f82ea7c3cbd4b69600)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | "system name" --> "operating system", rmv examples I think the connection with -s is still reasonably discernible, and the term OS is [...] | 2015-10-03T12:30:53 | [c4e1b051a7a7](https://github.com/tldr-pages/tldr/commit/c4e1b051a7a73037df552e77ba3046737dbab5ee)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | reorganize per discussion at #285 | 2015-07-08T19:45:35 | [1e763bedb98c](https://github.com/tldr-pages/tldr/commit/1e763bedb98c63f2523aa8e5e8fbf8f7e45b92d4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | improve example description, as agreed in #285 | 2015-07-06T13:39:39 | [f8a34b8f739e](https://github.com/tldr-pages/tldr/commit/f8a34b8f739e5725f1d065aff18a33c96d5d05ee)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | use a more useful second example grouping 3 related options that produce a more useful output. The descriptions are in the same order [...] | 2015-07-01T21:57:51 | [89a6b90afddf](https://github.com/tldr-pages/tldr/commit/89a6b90afddf97449dfe57ac255568b8efeb9407)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

