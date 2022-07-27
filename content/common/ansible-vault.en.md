---
author: ['Marcus Grant']
date: 1578957089
title: "ansible-vault, TLDR Pages"
description: "ansible-vault, Encrypts & decrypts values, data structures and files within Ansible projects."
categories: "common"
---
> More information: <https://docs.ansible.com/ansible/latest/user_guide/vault.html#id17>.

- Create a new encrypted vault file with a prompt for a password:

```bash
ansible-vault create vault_file
```

- Create a new encrypted vault file using a vault key file to encrypt it:

```bash
ansible-vault create --vault-password-file=password_file vault_file
```

- Encrypt an existing file using an optional password file:

```bash
ansible-vault encrypt --vault-password-file=password_file vault_file
```

- Encrypt a string using Ansible's encrypted string format, displaying interactive prompts:

```bash
ansible-vault encrypt_string
```

- View an encrypted file, using a password file to decrypt:

```bash
ansible-vault view --vault-password-file=password_file vault_file
```

- Re-key already encrypted vault file with a new password file:

```bash
ansible-vault rekey --vault-password-file=old_password_file --new-vault-password-file=new_password_file vault_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marcus Grant](mailto:marcusfg@gmail.com) | ansible-vault: add page (#3279) | 2020-01-14T00:11:29 | [2694e7caf307](https://github.com/tldr-pages/tldr/commit/2694e7caf3070eb396c9fde0d3f49041662573f2)

