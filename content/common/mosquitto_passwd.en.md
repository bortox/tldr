---
author: ['Starbeamrainbowlabs']
date: 1565428727
title: "mosquitto_passwd"
description: "mosquitto_passwd, Manage password files for mosquitto."
categories: "common"
---
> See also `mosquitto`, the MQTT server that this manages.

> More information: <https://mosquitto.org/man/mosquitto_passwd-1.html>.

- Add a new user to a password file (will prompt to enter the password):

```bash
mosquitto_passwd path/to/password_file username
```

- Create the password file if it doesn't already exist:

```bash
mosquitto_passwd -c path/to/password_file username
```

- Delete the specified username instead:

```bash
mosquitto_passwd -D path/to/password_file username
```

- Upgrade an old plain-text password file to a hashed password file:

```bash
mosquitto_passwd -U path/to/password_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | mosquitto_passwd: add page (#3232) | 2019-08-10T11:18:47 | [e55edff06dcd](https://github.com/tldr-pages/tldr/commit/e55edff06dcda988fa741d4ec13ad9cd0168348e)

