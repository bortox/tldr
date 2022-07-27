---
author: ['Owen Voke', 'Marco Bonelli', 'Jeroen Meulemeester', 'Ivan Aracki', 'Guido Lena Cota']
date: 1582813206
title: "vault, TLDR Pages"
description: "vault, A CLI to interact with HashiCorp Vault."
categories: "common"
---
> More information: <https://www.vaultproject.io/docs/commands>.

- Connect to a Vault server and initialize a new encrypted data store:

```bash
vault init
```

- Unseal (unlock) the vault, by providing one of the key shares needed to access the encrypted data store:

```bash
vault unseal key-share-x
```

- Authenticate the CLI client against the Vault server, using an authentication token:

```bash
vault auth authentication_token
```

- Store a new secret in the vault, using the generic back-end called "secret":

```bash
vault write secret/hello value=world
```

- Read a value from the vault, using the generic back-end called "secret":

```bash
vault read secret/hello
```

- Read a specific field from the value:

```bash
vault read -field=field_name secret/hello
```

- Seal (lock) the Vault server, by removing the encryption key of the data store from memory:

```bash
vault seal
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | vault: add command (#3871) | 2020-02-27T15:20:06 | [649e2f6590a6](https://github.com/tldr-pages/tldr/commit/649e2f6590a6b38adf0864f2e07e1d29cd7a2f88)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mass change: apply snake case to tokens (#2518) | 2018-10-29T12:14:25 | [18370557b25e](https://github.com/tldr-pages/tldr/commit/18370557b25e5340d9ee5cfeee346ce8fcb4ef95)
[Jeroen Meulemeester](mailto:jeroen.meulemeester@gmail.com) | vault: Fix punctuation review remarks | 2017-09-08T16:36:06 | [0ddfb4fcf10d](https://github.com/tldr-pages/tldr/commit/0ddfb4fcf10dab6e8af2a7c19203cb2d8de5190a)
[Jeroen Meulemeester](mailto:jeroen.meulemeester@gmail.com) | vault: Simplify examples and prevent jargon - Simplified 'init' command, using the defaults - Provide synonym 'unlock' to explain the [...] | 2017-09-08T14:21:37 | [98ccb025514c](https://github.com/tldr-pages/tldr/commit/98ccb025514c2b4f82615da75efb7d26057e4858)
[Jeroen Meulemeester](mailto:jeroen.meulemeester@gmail.com) | vault: Fix 'comma/comment' remarks | 2017-09-08T07:40:26 | [8e75c501729b](https://github.com/tldr-pages/tldr/commit/8e75c501729b8aaa2d68fb04f30c130421a7c758)
[Jeroen Meulemeester](mailto:jeroen.meulemeester@gmail.com) | vault: Fix 'vault write' remarks Vault uses different back-ends (secret, auth, audit, ..), which are modeled as a kind of file system: [...] | 2017-09-07T21:39:50 | [3074e54c5d5c](https://github.com/tldr-pages/tldr/commit/3074e54c5d5c9b36b6390a0250c95c40a4be3a97)
[Jeroen Meulemeester](mailto:jeroen.meulemeester@gmail.com) | vault: Fix some review remarks | 2017-09-07T18:50:18 | [2ae4673c9d80](https://github.com/tldr-pages/tldr/commit/2ae4673c9d805769d9911711c93a31a2b18b81a7)
[Jeroen Meulemeester](mailto:jeroen.meulemeester@gmail.com) | vault: add page | 2017-09-07T18:35:24 | [f10ea81e3e7d](https://github.com/tldr-pages/tldr/commit/f10ea81e3e7deb2d5a312e123751e81211e8324f)

