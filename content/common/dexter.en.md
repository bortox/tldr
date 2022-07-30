---
author: ['Ivan Aracki', 'Guido Lena Cota', 'Marco Bonelli']
date: 1604238005
title: "dexter"
description: "dexter, Tool for authenticating the kubectl users with OpenId Connect."
categories: "common"
---
> More information: <https://github.com/gini/dexter>.

- Create and authenticate a user with Google OIDC:

```bash
dexter auth -i client_id -s client_secret
```

- Override the default kube config location:

```bash
dexter auth -i client_id -s client_secret --kube-config sample/config
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | dexter: add page (#3040) | 2019-05-20T13:33:22 | [a269fe759507](https://github.com/tldr-pages/tldr/commit/a269fe7595071a5e18be3990c9bb8b7230457117)

