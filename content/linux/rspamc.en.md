---
author: ['bl-ue', 'Starbeamrainbowlabs', 'Emily Grace Seville']
date: 1647882468
title: "rspamc, TLDR Pages"
description: "rspamc, Command-line client for rspamd servers."
categories: "linux"
---
> More information: <https://manned.org/rspamc>.

- Train the bayesian filter to recognise an email as spam:

```bash
rspamc learn_spam path/to/email_file
```

- Train the bayesian filter to recognise an email as ham:

```bash
rspamc learn_ham path/to/email_file
```

- Generate a manual report on an email:

```bash
rspamc symbols path/to/email_file
```

- Show server statistics:

```bash
rspamc stat
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | rspamc: add page (#1612) | 2017-10-30T20:21:45 | [c69045c6bbfb](https://github.com/tldr-pages/tldr/commit/c69045c6bbfb4c88a2b0eede46fb0fa3fbeecde7)

