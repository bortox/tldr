---
author: ['Charles Levine', 'bl-ue']
date: 1621541621
title: "travis, TLDR Pages"
description: "travis, Command-line client to interface with Travis CI."
categories: "common"
---
> More information: <https://github.com/travis-ci/travis.rb>.

- Display the client version:

```bash
travis version
```

- Authenticate the CLI client against the server, using an authentication token:

```bash
travis login
```

- List repositories the user has permissions on:

```bash
travis repos
```

- Encrypt values in `.travis.yml`:

```bash
travis encrypt token
```

- Generate a `.travis.yml` file and enable the project:

```bash
travis init
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Charles Levine](mailto:52892481+charlielevine@users.noreply.github.com) | travis: add page (#4744) | 2020-11-01T03:16:33 | [377c9e57d66c](https://github.com/tldr-pages/tldr/commit/377c9e57d66c1314315c70b30ea03abfec5f2f08)

