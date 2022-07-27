---
author: ['Waldir Pimenta', 'Inesgor', 'Marco Bonelli', 'CleanMachine1', 'Michishige Kaito', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629050349
title: "tomb, TLDR Pages"
description: "tomb, Manage encrypted storage directories that can be safely transported and hidden in a filesystem."
categories: "linux"
---
> More information: <https://www.dyne.org/software/tomb/>.

- Create a new tomb with an initial size of 100 MB:

```bash
tomb dig -s 100 encrypted_directory.tomb
```

- Create a new key file that can be used to lock a tomb; user will be prompted for a password for the key:

```bash
tomb forge encrypted_directory.tomb.key
```

- Forcefully create a new key, even if the tomb isn't allowing key forging (due to swap):

```bash
tomb forge encrypted_directory.tomb.key -f
```

- Initialize and lock an empty tomb using a key made with `forge`:

```bash
tomb lock encrypted_directory.tomb -k encrypted_directory.tomb.key
```

- Mount a tomb (by default in `/media`) using its key, making it usable as a regular filesystem directory:

```bash
tomb open encrypted_directory.tomb -k encrypted_directory.tomb.key
```

- Close a tomb (fails if the tomb is being used by a process):

```bash
tomb close encrypted_directory.tomb
```

- Forcefully close all open tombs, killing any applications using them:

```bash
tomb slam all
```

- List all open tombs:

```bash
tomb list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Inesgor](mailto:81314876+Inesgor@users.noreply.github.com) | fc-pattern, sv, tomb, xkill: add examples (#6121) | 2021-07-24T21:12:04 | [3c2ddfbccca1](https://github.com/tldr-pages/tldr/commit/3c2ddfbccca1824d61550b57338503dd5572ccaa)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | terminator, timedatectl, tomb: add more information links (#6122) | 2021-06-14T19:49:31 | [03b66517c464](https://github.com/tldr-pages/tldr/commit/03b66517c46473067fde377781960f55fcd0ded8)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | wrap 100 in token format; mention password prompt | 2017-04-27T07:34:54 | [724ec3d5de47](https://github.com/tldr-pages/tldr/commit/724ec3d5de47fdb335c7bd3831004342abc7c312)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | tomb: fix syntax to match guidelines | 2017-04-27T07:34:54 | [8241783af1bb](https://github.com/tldr-pages/tldr/commit/8241783af1bb72448435ac1e8f938481bd22db76)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | tomb: edit page to conform to tldr guidelines also improve example descriptions to better match the documentation in [...] | 2017-04-27T07:34:54 | [0c602a263f9e](https://github.com/tldr-pages/tldr/commit/0c602a263f9e68ea1dc307fa1774107400413b22)
[Michishige Kaito](mailto:me@mkaito.com) | Fix lint issues. | 2017-04-27T07:34:54 | [c0d16b2f7e98](https://github.com/tldr-pages/tldr/commit/c0d16b2f7e9848290263545750ae2c939c22e908)
[Michishige Kaito](mailto:me@mkaito.com) | tomb: add page | 2017-04-27T07:34:54 | [972e5889e1d3](https://github.com/tldr-pages/tldr/commit/972e5889e1d336126375e7845ff98cbd795e7902)

