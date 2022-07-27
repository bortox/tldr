---
author: ['Stig124', 'RH-sdavey', 'Starbeamrainbowlabs']
date: 1625841955
title: "disown, TLDR Pages"
description: "disown, Allow sub-processes to live beyond the shell that they are attached to."
categories: "linux"
---
> See also the `jobs` command.

> More information: <https://www.gnu.org/software/bash/manual/bash.html#index-disown>.

- Disown the current job:

```bash
disown
```

- Disown a specific job:

```bash
disown %job_number
```

- Disown all jobs:

```bash
disown -a
```

- Keep job (do not disown it), but mark it so that no future SIGHUP is received on shell exit:

```bash
disown -h %job_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[RH-sdavey](mailto:32485509+RH-sdavey@users.noreply.github.com) | disown: add -h example (#3007) | 2019-05-14T19:17:37 | [d7cffae11e49](https://github.com/tldr-pages/tldr/commit/d7cffae11e491add738562e884bd1318a42d738a)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | disown: add page (#2200) | 2018-07-17T21:29:16 | [5cf741400ddf](https://github.com/tldr-pages/tldr/commit/5cf741400ddfca6e1a03db67526dff6bc65ba514)

