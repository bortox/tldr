---
author: ['FantasyCookie17']
date: 1618877653
title: "age"
description: "age, A simple, modern and secure file encryption tool."
categories: "common"
---
> More information: <https://age-encryption.org>.

- Generate an encrypted file that can be decrypted with a passphrase:

```bash
age --passphrase --output path/to/encrypted_file path/to/unencrypted_file
```

- Generate a key pair, saving the private key to an unencrypted file and printing the public key to stdout:

```bash
age-keygen --output path/to/file
```

- Encrypt a file with one or more public keys that are entered as literals:

```bash
age --recipient public_key_1 --recipient public_key_2 path/to/unencrypted_file --output path/to/encrypted_file
```

- Encrypt a file with one or more public keys that are specified in a recipients file:

```bash
age --recipients-file path/to/recipients_file path/to/unencrypted_file --output path/to/encrypted_file
```

- Decrypt a file with a passphrase:

```bash
age --decrypt --output path/to/decrypted_file path/to/encrypted_file
```

- Decrypt a file with a private key file:

```bash
age --decrypt --identity path/to/private_key_file --output path/to/decrypted_file path/to/encrypted_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | age: add page (#5758) | 2021-04-20T02:14:13 | [f5469ee92cbd](https://github.com/tldr-pages/tldr/commit/f5469ee92cbde6827bad858b6709c8d9a5d50c08)

