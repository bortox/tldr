---
author: ['bl-ue', 'marchersimon', 'Yurii Rochniak']
date: 1621541621
title: "aws-google-auth, TLDR Pages"
description: "aws-google-auth, Command-line tool to acquire AWS temporary (STS) credentials using Google Apps as a federated (Single Sign-On) provider."
categories: "common"
---
> More information: <https://github.com/cevoaustralia/aws-google-auth>.

- Log in with Google SSO using the IDP and SP identifiers and set the credentials duration to one hour:

```bash
aws-google-auth -u example@example.com -I $GOOGLE_IDP_ID -S $GOOGLE_SP_ID -d 3600
```

- Log in [a]sking which role to use (in case of several available SAML roles):

```bash
aws-google-auth -u example@example.com -I $GOOGLE_IDP_ID -S $GOOGLE_SP_ID -d 3600 -a
```

- Resolve aliases for AWS accounts:

```bash
aws-google-auth -u example@example.com -I $GOOGLE_IDP_ID -S $GOOGLE_SP_ID -d 3600 -a --resolve-aliases
```

- Show help information:

```bash
aws-google-auth -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Yurii Rochniak](mailto:yrochnyak@gmail.com) | aws-google-auth: add page (#3287) | 2019-10-03T09:59:00 | [bb5bd628b787](https://github.com/tldr-pages/tldr/commit/bb5bd628b7875509261f1a6995d55c4e73b28bfe)

