---
author: ['lord63', 'Minh Nguyen', 'Laurent Indermühle', 'hemanth.hm', 'Ruben Vereecken', 'Agniva De Sarker', 'Martin Pool', 'kalebo', 'Lucas Gabriel Schneider', 'Starbeamrainbowlabs']
date: 1612112718
title: "sudo, TLDR Pages"
description: "sudo, Executes a single command as the superuser or another user."
categories: "common"
---
> More information: <https://www.sudo.ws/sudo.html>.

- Run a command as the superuser:

```bash
sudo less /var/log/syslog
```

- Edit a file as the superuser with your default editor:

```bash
sudo --edit /etc/fstab
```

- Run a command as another user and/or group:

```bash
sudo --user=user --group=group id -a
```

- Repeat the last command prefixed with `sudo` (only in `bash`, `zsh`, etc.):

```bash
sudo !!
```

- Launch the default shell with superuser privileges and run login-specific files (`.profile`, `.bash_profile`, etc.):

```bash
sudo --login
```

- Launch the default shell with superuser privileges without changing the environment:

```bash
sudo --shell
```

- Launch the default shell as the specified user, loading the user's environment and reading login-specific files (`.profile`, `.bash_profile`, etc.):

```bash
sudo --login --user=user
```

- List the allowed (and forbidden) commands for the invoking user:

```bash
sudo --list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Laurent Indermühle](mailto:honiix@pm.me) | sudo: add --login, --shell and --list examples (#5202) add more information link | 2021-01-30T22:04:40 | [d8be3f35a37a](https://github.com/tldr-pages/tldr/commit/d8be3f35a37a5654563ef5238d6b9ea8eb46eecf)
[kalebo](mailto:kaleb.olson@gmail.com) | sudo: remove ambiguity in example (#2585) | 2018-11-13T16:45:28 | [58633331063b](https://github.com/tldr-pages/tldr/commit/58633331063b031cd0f95dd0357f15a8f8065594)
[kalebo](mailto:kaleb.olson@gmail.com) | Make examples more benign | 2018-11-12T11:32:17 | [6d32be73d192](https://github.com/tldr-pages/tldr/commit/6d32be73d1924dae3d5ccddc754d2d08f9c003cd)
[kalebo](mailto:kaleb.olson@gmail.com) | sudo: general revision of entry | 2018-11-12T11:32:17 | [84713e06effd](https://github.com/tldr-pages/tldr/commit/84713e06effdb44777cc7b75364f183617713596)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | sudo: changed wording to indicate default shell | 2017-11-29T04:27:56 | [49468f7b4813](https://github.com/tldr-pages/tldr/commit/49468f7b4813bae8e643b4e202309de174489ce3)
[Minh Nguyen](mailto:minh@mnguyen.io) | sudo: Reword launch shell example | 2017-11-29T00:59:03 | [8d002cd40628](https://github.com/tldr-pages/tldr/commit/8d002cd406281c13e2ce888053e633cde9a7c691)
[Minh Nguyen](mailto:minh@mnguyen.io) | sudo: Change to use flag -i for macOS | 2017-11-27T08:14:18 | [38788de92a2f](https://github.com/tldr-pages/tldr/commit/38788de92a2f6ed7fc47826cbd48e9d1b720fd82)
[Minh Nguyen](mailto:minh@mnguyen.io) | sudo: Add example to run an interactive shell | 2017-11-27T07:48:29 | [4c9f12072e3c](https://github.com/tldr-pages/tldr/commit/4c9f12072e3c2db369810857d81ed248c09af196)
[Minh Nguyen](mailto:minh@mnguyen.io) | Revert "sudo: add example for interactive shell" This reverts commit 415d4834eab0ec192a44dd8354d46d7df0f7ea8f. | 2017-11-27T07:19:13 | [bcd4efd8857b](https://github.com/tldr-pages/tldr/commit/bcd4efd8857b3d75d70f3395ca94bffca2bfd841)
[Minh Nguyen](mailto:minh@mnguyen.io) | sudo: add example for interactive shell | 2017-11-27T07:09:29 | [415d4834eab0](https://github.com/tldr-pages/tldr/commit/415d4834eab0ec192a44dd8354d46d7df0f7ea8f)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Update sudo.md | 2017-10-02T06:20:47 | [e8fe8aaa9e40](https://github.com/tldr-pages/tldr/commit/e8fe8aaa9e40487feb11cbc4edb30f04f94962c4)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | sudo: Improve grammar | 2017-10-02T06:20:47 | [d6d57e8f6f8a](https://github.com/tldr-pages/tldr/commit/d6d57e8f6f8a09681e3985d362a52c527a0f59ed)
[Martin Pool](mailto:mbp@sourcefrog.net) | sudo: use `shutdown -h` to halt rather than reboot (#1191) Makes the example consistent with its description | 2016-12-06T14:39:45 | [fe37d4fb838e](https://github.com/tldr-pages/tldr/commit/fe37d4fb838e052f7268b35133e28a21caafd5be)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[hemanth.hm](mailto:hemanth.hm@gmail.com) | Better formatting. | 2014-06-27T18:01:28 | [7e5ba0ce48ef](https://github.com/tldr-pages/tldr/commit/7e5ba0ce48efafa7d75eb3e541feb3a6469d824d)
[hemanth.hm](mailto:hemanth.hm@gmail.com) | Adding docs for 'sudo' | 2014-06-26T15:12:56 | [c21f4de00e96](https://github.com/tldr-pages/tldr/commit/c21f4de00e9610976f5b93d5e4b69079abc8b48b)

