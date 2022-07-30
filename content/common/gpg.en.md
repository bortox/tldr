---
author: ['Waldir Pimenta', 'André König', 'Romain Prieto', 'Lucas Gabriel Schneider', 'Rob Young', 'lord63', 'pxgamer', 'Matthew Peveler', 'HairyFotr', 'nikostr', 'CleanMachine1', 'Ruben Vereecken']
date: 1654196591
title: "gpg"
description: "gpg, GNU Privacy Guard."
categories: "common"
---
> See `gpg2` for GNU Privacy Guard 2. Most operating systems symlink `gpg` to `gpg2`.

> More information: <https://gnupg.org>.

- Create a GPG public and private key interactively:

```bash
gpg --full-generate-key
```

- Sign `doc.txt` without encryption (writes output to `doc.txt.asc`):

```bash
gpg --clearsign doc.txt
```

- Encrypt and sign `doc.txt` for alice@example.com and bob@example.com (output to `doc.txt.gpg`):

```bash
gpg --encrypt --sign --recipient alice@example.com --recipient bob@example.com doc.txt
```

- Encrypt `doc.txt` with only a passphrase (output to `doc.txt.gpg`):

```bash
gpg --symmetric doc.txt
```

- Decrypt `doc.txt.gpg` (output to stdout):

```bash
gpg --decrypt doc.txt.gpg
```

- Import a public key:

```bash
gpg --import public.gpg
```

- Export public key for alice@example.com (output to stdout):

```bash
gpg --export --armor alice@example.com
```

- Export private key for alice@example.com (output to stdout):

```bash
gpg --export-secret-keys --armor alice@example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | gpg: add notice that command is often symlinked (#8110) | 2022-06-02T21:03:11 | [386687af1e7a](https://github.com/tldr-pages/tldr/commit/386687af1e7aa06b5651f471942ea1a8e07915f7)
[nikostr](mailto:nikostr@users.noreply.github.com) | gpg: add signing and multiple recipients (#8111) Update the `gpg` encryption example to indicate that multiple recipients and signing [...] | 2022-05-31T04:21:29 | [a7f4d795207e](https://github.com/tldr-pages/tldr/commit/a7f4d795207eb6635c4367690aa5401860e79585)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | gpg: add --full-generate-key example (#6195) Co-authored-by: Muhammad Falak R Wani <falakreyaz@gmail.com> | 2021-07-06T05:19:59 | [ec92caa35bd5](https://github.com/tldr-pages/tldr/commit/ec92caa35bd521dd23591afe02cc38e9ffe41040)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Matthew Peveler](mailto:matt.peveler@gmail.com) | gpg2: fix page title to match file name (#5090) Signed-off-by: Matthew Peveler <matt.peveler@gmail.com> | 2021-01-04T23:59:33 | [c25e4e378e4b](https://github.com/tldr-pages/tldr/commit/c25e4e378e4b0088ee541714e008e79d6e36a735)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | gpg: add link to homepage | 2019-06-07T23:58:59 | [1fefd4653f0f](https://github.com/tldr-pages/tldr/commit/1fefd4653f0ff5845e12ac5e573a4a056de6928b)
[HairyFotr](mailto:hairyfotr@gmail.com) | Fix a few typos | 2017-07-23T16:22:44 | [e0ccb7147a25](https://github.com/tldr-pages/tldr/commit/e0ccb7147a25b5d738e3991f399f87e45f3a4140)
[Rob Young](mailto:bubblenut@gmail.com) | Add examples for exporting GPG keys (#907) This chage adds examples for exporting public and private GPG keys. This is particularly [...] | 2016-06-21T00:58:28 | [b78dd4054775](https://github.com/tldr-pages/tldr/commit/b78dd4054775de38e0de957fa373ad5c3063b105)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[André König](mailto:andre.koenig@posteo.de) | GPG: Parameter for importing a public key. | 2014-08-13T20:48:25 | [b9f2e4dfe4fa](https://github.com/tldr-pages/tldr/commit/b9f2e4dfe4fa4d4982fe04d8c8c3ea2ac381954f)
[Romain Prieto](mailto:choicesmade@gmail.com) | GPG command As authored by @fordhurley. We had a little merge problem, so had to recreate this file on master. | 2014-05-27T00:49:33 | [b250569a6015](https://github.com/tldr-pages/tldr/commit/b250569a6015ee23ea61296ce25c7d1d2c43b1ef)

