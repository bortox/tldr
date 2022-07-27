---
author: ['Waldir Pimenta', 'Stig124', 'Kefei Lu', 'Nicolas Zachow', 'Seth Falco']
date: 1629050349
title: "cal, TLDR Pages"
description: "cal, Prints calendar information, with the current day highlighted."
categories: "linux"
---
> More information: <https://manned.org/cal>.

- Display a calendar for the current month:

```bash
cal
```

- Display previous, current and next month:

```bash
cal -3
```

- Use Monday as the first day of the week:

```bash
cal --monday
```

- Display a calendar for a specific year (4 digits):

```bash
cal year
```

- Display a calendar for a specific month and year:

```bash
cal month year
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Kefei Lu](mailto:kflu@users.noreply.github.com) | cal: add `-3` example (#2716) | 2019-01-27T05:49:38 | [66fce39b3708](https://github.com/tldr-pages/tldr/commit/66fce39b3708ea314fe8aeac8192dabe590e44f3)
[Nicolas Zachow](mailto:nicolas@nicolas.eti.br) | Removing skeaky space. | 2017-11-19T05:09:05 | [625d6c141315](https://github.com/tldr-pages/tldr/commit/625d6c141315803fbf191d6794e7ba7a2dea4cbc)
[Nicolas Zachow](mailto:nicolas@nicolas.eti.br) | cal: Add use case For clarity I changed "-m" to "--monday". Also, I've removed the "cal -y" for simplicity. You could just user "cal [...] | 2017-11-19T04:59:51 | [331400f96487](https://github.com/tldr-pages/tldr/commit/331400f9648740588e4451ec9a0324f62fd4db0c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cal: adjust osx version to make it more useful, and add linux version along the same lines | 2017-05-02T09:10:49 | [b3654135a86e](https://github.com/tldr-pages/tldr/commit/b3654135a86e75ab5edbc322452c93dad7dad2c0)

