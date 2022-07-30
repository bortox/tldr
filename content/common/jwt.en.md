---
author: ['Sakthivel Balasubramaniam', 'bl-ue']
date: 1621541621
title: "jwt"
description: "jwt, A command-line tool to work with JSON Web Tokens (JWTs)."
categories: "common"
---
> Encryption algorithms available are HS256, HS384, HS512, RS256, RS384, RS512, ES256, ES384.

> More information: <https://github.com/mike-engel/jwt-cli>.

- Decode a JWT:

```bash
jwt decode jwt_string
```

- Decode a JWT as a JSON string:

```bash
jwt decode -j jwt_string
```

- Encode a JSON string to a JWT:

```bash
jwt encode --alg HS256 --secret 1234567890 'json_string'
```

- Encode key pair payload to JWT:

```bash
jwt encode --alg HS256 --secret 1234567890 -P key=value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | jwt: add space in algorithm list in description (#5135) | 2021-01-11T17:14:01 | [c0ed70aa40f6](https://github.com/tldr-pages/tldr/commit/c0ed70aa40f665357cabe056f9d87d086dc0dbd8)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | jwt: fix more information link | 2021-01-08T09:38:18 | [8f9e1a045290](https://github.com/tldr-pages/tldr/commit/8f9e1a045290da2cf3038194be4c2fb9b5a0c058)
[Sakthivel Balasubramaniam](mailto:8691700+ImShakthi@users.noreply.github.com) | jwt: add page (#3350) | 2019-10-09T17:59:16 | [83aef83efa2b](https://github.com/tldr-pages/tldr/commit/83aef83efa2b5aafb4d680ed178d412de1af3c8d)

