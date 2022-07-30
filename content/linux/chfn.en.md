---
author: ['Stig124', 'lbonanomi']
date: 1625841955
title: "chfn"
description: "chfn, Update `finger` info for a user."
categories: "linux"
---
> More information: <https://manned.org/chfn>.

- Update a user's "Name" field in the output of `finger`:

```bash
chfn -f new_display_name username
```

- Update a user's "Office Room Number" field for the output of `finger`:

```bash
chfn -o new_office_room_number username
```

- Update a user's "Office Phone Number" field for the output of `finger`:

```bash
chfn -p new_office_telephone_number username
```

- Update a user's "Home Phone Number" field for the output of `finger`:

```bash
chfn -h new_home_telephone_number username
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[lbonanomi](mailto:5369016+lbonanomi@users.noreply.github.com) | chfn: add page (#2929) * Create chfn.md * Update chfn.md * chfn: tweak grammar | 2019-04-19T02:53:14 | [1c73992e8cc9](https://github.com/tldr-pages/tldr/commit/1c73992e8cc92658cbc943a3186d7b4c139f5548)

