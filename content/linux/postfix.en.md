---
author: ['marchersimon', 'Starbeamrainbowlabs']
date: 1625253777
title: "postfix, TLDR Pages"
description: "postfix, Postfix mail transfer agent (MTA) control program."
categories: "linux"
---
> See also `dovecot`, a mail delivery agent (MDA) that integrates with Postfix.

> More information: <http://www.postfix.org>.

- Check the configuration:

```bash
sudo postfix check
```

- Check the status of the Postfix daemon:

```bash
sudo postfix status
```

- Start Postfix:

```bash
sudo postfix start
```

- Gracefully stop Postfix:

```bash
sudo postfix stop
```

- Flush the mail queue:

```bash
sudo postfix flush
```

- Reload the configuration files:

```bash
sudo postfix reload
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | postfix: add page (#3875) | 2020-03-04T00:36:08 | [90407a0401e9](https://github.com/tldr-pages/tldr/commit/90407a0401e9d6a206c7b743582dfd10b6311724)

