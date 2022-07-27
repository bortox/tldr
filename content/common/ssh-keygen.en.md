---
author: ['Rob Young', 'Benjamin Tamasi', 'Ruben Vereecken', 'Valentin Vetter', 'syleung', 'Alexandru Duzsardi', 'Antonio', 'Andreas Gerler', 'Frits', 'Jonathan Dahan', 'Seth Falco', 'Starbeamrainbowlabs']
date: 1633351190
title: "ssh-keygen, TLDR Pages"
description: "ssh-keygen, Generate ssh keys used for authentication, password-less logins, and other things."
categories: "common"
---
> More information: <https://man.openbsd.org/ssh-keygen>.

- Generate a key interactively:

```bash
ssh-keygen
```

- Specify file in which to save the key:

```bash
ssh-keygen -f ~/.ssh/filename
```

- Generate an ed25519 key with 100 key derivation function rounds:

```bash
ssh-keygen -t ed25519 -a 100
```

- Generate an RSA 4096-bit key with email as a comment:

```bash
ssh-keygen -t dsa|ecdsa|ed25519|rsa -b 4096 -C "comment|email"
```

- Remove the keys of a host from the known_hosts file (useful when a known host has a new key):

```bash
ssh-keygen -R remote_host
```

- Retrieve the fingerprint of a key in MD5 Hex:

```bash
ssh-keygen -l -E md5 -f ~/.ssh/filename
```

- Change the password of a key:

```bash
ssh-keygen -p -f ~/.ssh/filename
```

- Change the type of the key format (for example from OPENSSH format to PEM), the file will be rewritten in-place:

```bash
ssh-keygen -p -N "" -m PEM -f ~/.ssh/OpenSSH_private_key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[Alexandru Duzsardi](mailto:aduzsardi@users.noreply.github.com) | ssh-keygen: add key format conversion (#6213) | 2021-08-17T20:03:15 | [2392183ef0f4](https://github.com/tldr-pages/tldr/commit/2392183ef0f4ad9668129409a8f5ba828f0f0ec1)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Benjamin Tamasi](mailto:half2me@users.noreply.github.com) | ssh-keygen: add -R example (#3645) | 2019-12-07T04:20:59 | [7941da3123ed](https://github.com/tldr-pages/tldr/commit/7941da3123eda64fae198ef75aaae6cdf6e7b5ef)
[Valentin Vetter](mailto:BeLi4L@users.noreply.github.com) | ssh-keygen: fix typo | 2019-09-06T12:00:53 | [be391ec40f76](https://github.com/tldr-pages/tldr/commit/be391ec40f76a28a72aeea44d742751dce08d5d1)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | ssh-keygen: Remove DSA example | 2018-02-06T19:34:51 | [5b8c7245fd25](https://github.com/tldr-pages/tldr/commit/5b8c7245fd25e171b7e51008c1907b75026419d7)
[Frits](mailto:frots@users.noreply.github.com) | ssh-keygen: Add ed25519 example | 2018-02-06T19:34:51 | [687d2c2ea5f9](https://github.com/tldr-pages/tldr/commit/687d2c2ea5f9f31024b85b022ee4d99aa07e9ff9)
[Rob Young](mailto:bubblenut@gmail.com) | Adds command to show SSH key fingerprint (#935) Adds an ssh-keygen command to show the fingerprint of an SSH key in the same format [...] | 2016-07-26T16:16:42 | [44527a82a89f](https://github.com/tldr-pages/tldr/commit/44527a82a89f38a8f2c497ceaf7b2c24640b6b26)
[Andreas Gerler](mailto:baron@bundesbrandschatzamt.de) | ssh-keygen: change passphrase for ssh-key - add info for changing password of an existing ssh-key Signed-off-by: Andreas Gerler [...] | 2016-06-01T11:15:10 | [4d8497271f6e](https://github.com/tldr-pages/tldr/commit/4d8497271f6e1486f755d2eb2a974f957b6ec8b7)
[Jonathan Dahan](mailto:jdehan@etsy.com) | ssh-keygen: add output file path option | 2016-03-09T23:10:49 | [3902255b9dbc](https://github.com/tldr-pages/tldr/commit/3902255b9dbc9d565866960b90f44b6839615580)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed damage done by formatter some time ago | 2016-01-28T12:41:42 | [b4304e105004](https://github.com/tldr-pages/tldr/commit/b4304e1050045b410af4ac90f71a90aeb506de44)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Antonio](mailto:antoniom13) | add ssh-keygen builds up to options Updates verbiage | 2016-01-10T18:19:50 | [626168288855](https://github.com/tldr-pages/tldr/commit/626168288855b64cddfbc9a5d85982f2d1bde970)

