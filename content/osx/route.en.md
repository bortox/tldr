---
author: ['Ruben Vereecken', 'Rikesh Ramlochund', 'Axel Colin de Verdiere', 'Emily Grace Seville']
date: 1644837703
title: "route, TLDR Pages"
description: "route, Manually manipulate the routing tables."
categories: "osx"
---
> Necessitates to be root.

> More information: <https://www.manpagez.com/man/8/route/>.

- Add a route to a destination through a gateway:

```bash
sudo route add "destination_ip_address" "gateway_address"
```

- Add a route to a /24 subnet through a gateway:

```bash
sudo route add "subnet_ip_address/24" "gateway_address"
```

- Run in test mode (does not do anything, just print):

```bash
sudo route -t add "destination_ip_address/24" "gateway_address"
```

- Remove all routes:

```bash
sudo route flush
```

- Delete a specific route:

```bash
sudo route delete "destination_ip_address/24"
```

- Lookup and display the route for a destination (hostname or IP address):

```bash
sudo route get "destination"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Rikesh Ramlochund](mailto:rrikesh@gmail.com) | route: add get | 2017-11-27T07:50:25 | [3ca3fc8b459b](https://github.com/tldr-pages/tldr/commit/3ca3fc8b459bc25f89a820434ddbdc8965e9bb83)
[Rikesh Ramlochund](mailto:rrikesh@gmail.com) | Add tldr for `route get {{destination}}` | 2017-11-27T07:45:40 | [df4185b548f3](https://github.com/tldr-pages/tldr/commit/df4185b548f3d572ce6dc3070657f4e77e93564b)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Axel Colin de Verdiere](mailto:axel@axelcdv.com) | Show a line with /24 subnet | 2014-03-07T14:34:37 | [be239f7a9f9a](https://github.com/tldr-pages/tldr/commit/be239f7a9f9a1929aa2e0c58ce856209dbdfbf51)
[Axel Colin de Verdiere](mailto:axel@axelcdv.com) | Added descriptive names for the arguments for route | 2014-03-07T01:03:24 | [efc526f61b09](https://github.com/tldr-pages/tldr/commit/efc526f61b098535dec75c0b9ee462bb3c42760b)
[Axel Colin de Verdiere](mailto:axel@axelcdv.com) | Added page for route under osx | 2014-03-06T17:47:59 | [124998b65a35](https://github.com/tldr-pages/tldr/commit/124998b65a35dc5b8fe41cb33ca548ea7eb10514)

