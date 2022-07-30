---
author: ['Kalaiarasan Somasundaram']
date: 1656070950
title: "chpasswd"
description: "chpasswd, Change the passwords for multiple users by using stdin."
categories: "linux"
---
> More information: <https://manned.org/chpasswd.8>.

- Change the password for a specific user:

```bash
printf "username:new_password" | sudo chpasswd
```

- Change the passwords for multiple users (The input text must not contain any spaces.):

```bash
printf "username_1:new_password_1\nusername_2:new_password_2" | sudo chpasswd
```

- Change the password for a specific user, and specify it in encrypted form:

```bash
printf "username:new_encrypted_password" | sudo chpasswd --encrypted
```

- Change the password for a specific user, and use a specific encryption for the stored password:

```bash
printf "username:new_password" | sudo chpasswd --crypt-method NONE|DES|MD5|SHA256|SHA512
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kalaiarasan Somasundaram](mailto:44941115+Kalaiz@users.noreply.github.com) | chpasswd: add page (#8145) | 2022-06-24T13:42:30 | [944c6daeb764](https://github.com/tldr-pages/tldr/commit/944c6daeb764cc9399ee66843b26e7b4130fa24f)

