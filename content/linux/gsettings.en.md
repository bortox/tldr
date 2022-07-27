---
author: ['yump']
date: 1626994925
title: "gsettings, TLDR Pages"
description: "gsettings, Query and modify dconf settings with schema validation."
categories: "linux"
---
> More information: <https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/using_the_desktop_environment_in_rhel_8/configuring-gnome-at-low-level_using-the-desktop-environment-in-rhel-8#using-gsettings-command_configuring-gnome-at-low-level>.

- Set the value of a key. Fails if the key doesn't exist or the value is out of range:

```bash
gsettings set org.example.schema example-key value
```

- Print the value of a key or the schema-provided default if the key has not been set in `dconf`:

```bash
gsetings get org.example.schema example-key
```

- Unset a key, so that its schema default value will be used:

```bash
gsettings reset org.example.schema example-key
```

- Display all (non-relocatable) schemas, keys, and values:

```bash
gsettings list-recursively
```

- Display all keys and values (default if not set) from one schema:

```bash
gsettings list-recursively org.example.schema
```

- Display schema-allowed values for a key (helpful with enum keys):

```bash
gsettings range org.example.schema example-key
```

- Display the human-readable description of a key:

```bash
gsettings describe org.example.schema example-key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[yump](mailto:yump@users.noreply.github.com) | gsettings: add page (#6251) | 2021-07-23T01:02:05 | [531b0486ce0f](https://github.com/tldr-pages/tldr/commit/531b0486ce0f485f93e8a043f6bead27883d2669)

