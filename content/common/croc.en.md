---
author: ['siavashsoleymani', 'bl-ue', 'Petter Salminen']
date: 1610307737
title: "croc"
description: "croc, Send and receive files easily and securely over any network."
categories: "common"
---
> More information: <https://github.com/schollz/croc>.

- Send a file or directory:

```bash
croc send path/to/file_or_directory
```

- Send a file or directory with a specific passphrase:

```bash
croc send --code passphrase path/to/file_or_directory
```

- Receive a file or directory on receiving machine:

```bash
croc passphrase
```

- Send and connect over a custom relay:

```bash
croc --relay ip_to_relay send path/to/file_or_directory
```

- Receive and connect over a custom relay:

```bash
croc --relay ip_to_relay passphrase
```

- Host a croc relay on the default ports:

```bash
croc relay
```

- Display parameters and options for a croc command:

```bash
croc send|relay --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | croc: change folder to directory | 2021-01-10T20:42:17 | [95e286e87af9](https://github.com/tldr-pages/tldr/commit/95e286e87af987e6153db51ad205c70efb510675)
[siavashsoleymani](mailto:siavash.solimanii@yahoo.com) | croc: fix typo | 2020-10-27T12:01:11 | [c6b1293bce1c](https://github.com/tldr-pages/tldr/commit/c6b1293bce1cdf842b87984382574e6a9f3a52e9)
[Petter Salminen](mailto:kazie@users.noreply.github.com) | croc: add page (#3917) | 2020-03-23T11:38:13 | [58af8f8eb267](https://github.com/tldr-pages/tldr/commit/58af8f8eb267980fe3912e552ff52b3fccb2c445)

