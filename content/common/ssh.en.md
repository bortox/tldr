---
author: ['Waldir Pimenta', 'Denis Sokolov', 'Agniva De Sarker', '汪東陽', 'quarcu', 'Paul', 'rprieto', 'Axel Navarro', 'lord63', 'Starbeamrainbowlabs', 'Phil Enzler', 'Pu Du', 'Bengt Brodersen', 'Ruben Vereecken']
date: 1642350498
title: "ssh"
description: "ssh, Secure Shell is a protocol used to securely log onto remote systems."
categories: "common"
---
> It can be used for logging or executing commands on a remote server.

> More information: <https://man.openbsd.org/ssh>.

- Connect to a remote server:

```bash
ssh username@remote_host
```

- Connect to a remote server with a specific identity (private key):

```bash
ssh -i path/to/key_file username@remote_host
```

- Connect to a remote server using a specific port:

```bash
ssh username@remote_host -p 2222
```

- Run a command on a remote server with a [t]ty allocation allowing interaction with the remote command:

```bash
ssh username@remote_host -t command command_arguments
```

- SSH tunneling: Dynamic port forwarding (SOCKS proxy on `localhost:1080`):

```bash
ssh -D 1080 username@remote_host
```

- SSH tunneling: Forward a specific port (`localhost:9999` to `example.org:80`) along with disabling pseudo-[T]ty allocation and executio[N] of remote commands:

```bash
ssh -L 9999:example.org:80 -N -T username@remote_host
```

- SSH jumping: Connect through a jumphost to a remote server (Multiple jump hops may be specified separated by comma characters):

```bash
ssh -J username@jump_host username@remote_host
```

- Agent forwarding: Forward the authentication information to the remote machine (see `man ssh_config` for available options):

```bash
ssh -A username@remote_host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[汪東陽](mailto:michael19920327@gmail.com) | ssh: fix typo (#7666) | 2022-01-16T17:28:18 | [0c961545eda7](https://github.com/tldr-pages/tldr/commit/0c961545eda78913472910ccb2e48117f93acb0e)
[Axel Navarro](mailto:navarroaxel@gmail.com) | ssh: add -t in example description (#6604) | 2021-10-03T16:39:34 | [3656eb90e73a](https://github.com/tldr-pages/tldr/commit/3656eb90e73a5f19db98f179d2a1191c551573f0)
[Phil Enzler](mailto:phil@pushbutton.studio) | ssh: remove -C and use SOCKS port (#5771) | 2021-04-16T03:47:49 | [38c3b011dc62](https://github.com/tldr-pages/tldr/commit/38c3b011dc62cb45b7c2df5708bd3a6a02ec0fe3)
[Paul](mailto:Lappro@users.noreply.github.com) | ssh: Remove real domains to remain neutral (#2999) Real domains should not be used as to alleviate bias and prevent people [...] | 2019-05-09T18:07:48 | [a6837c71b815](https://github.com/tldr-pages/tldr/commit/a6837c71b815ad9f06db8823a90f785c1b9d332a)
[Bengt Brodersen](mailto:bengt.brodersen@gmail.com) | ssh: add -J and -A flags (#2148) | 2018-06-21T07:21:47 | [31b664ccd822](https://github.com/tldr-pages/tldr/commit/31b664ccd8228fc075e88a0f2db7608feca60d67)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | ssh: shorten last description | 2016-10-18T09:31:23 | [f862a8aec23d](https://github.com/tldr-pages/tldr/commit/f862a8aec23d7c50c84c9162a84f9c9e100f3812)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Fix linting error | 2016-10-18T07:04:51 | [452ba5f903c0](https://github.com/tldr-pages/tldr/commit/452ba5f903c07b976b4093903611d6bd52ab35a6)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | ssh: simplify page - Combined the last 2 commands into a single format that can be expanded upon by showing the -o option, since both [...] | 2016-10-18T06:57:47 | [19156aa83dcd](https://github.com/tldr-pages/tldr/commit/19156aa83dcde2da459669d3f48d1fc8731e4684)
[Pu Du](mailto:rocketsboy@gmail.com) | ssh: add x11 forwarding | 2016-10-18T06:37:00 | [a9dc22e4dc47](https://github.com/tldr-pages/tldr/commit/a9dc22e4dc47c9d1fdb5114a2426c78fa67f6606)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | page format: lowercase command names consistently (#1083) | 2016-09-22T09:03:38 | [107248374447](https://github.com/tldr-pages/tldr/commit/1072483744475ab5a25c87e8eb7ed10c99dd6ed8)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Correct english in ssh page | 2016-01-15T15:41:03 | [66fd296d0610](https://github.com/tldr-pages/tldr/commit/66fd296d0610e5e239ef87ead32fe3694895d82b)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Denis Sokolov](mailto:denis@sokolov.cc) | ssh: remove quotes around remote command | 2016-01-05T19:37:25 | [61634c9703b2](https://github.com/tldr-pages/tldr/commit/61634c9703b25814bbda639dbbdba57be664dad3)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[quarcu](mailto:quarcu@users.noreply.github.com) | Update ssh.md | 2014-08-27T00:36:49 | [b2b80ed78a77](https://github.com/tldr-pages/tldr/commit/b2b80ed78a77e0c7729b22012db24a1abbebf159)
[quarcu](mailto:quarcu@users.noreply.github.com) | Update ssh.md Allow agent forward. Useful when working with ssh jumpbox. | 2014-08-27T00:33:18 | [939378295c67](https://github.com/tldr-pages/tldr/commit/939378295c670ccc57e71b29ab47da310347da22)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

