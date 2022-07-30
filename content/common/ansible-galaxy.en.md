---
author: ['Brandon Soto', 'Adrian Wyssmann', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1625740037
title: "ansible-galaxy"
description: "ansible-galaxy, Create and manage Ansible roles."
categories: "common"
---
> More information: <https://docs.ansible.com/ansible/latest/cli/ansible-galaxy.html>.

- Install a role:

```bash
ansible-galaxy install username.role_name
```

- Remove a role:

```bash
ansible-galaxy remove username.role_name
```

- List installed roles:

```bash
ansible-galaxy list
```

- Search for a given role:

```bash
ansible-galaxy search role_name
```

- Create a new role:

```bash
ansible-galaxy init role_name
```

- Get information about a user role:

```bash
ansible-galaxy role info username.role_name
```

- Get information about a collection:

```bash
ansible-galaxy collection info username.collection_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrian Wyssmann](mailto:papanito@wyssmann.com) | ansible-galaxy: add role info and collection info examples (#6187) | 2021-07-08T12:27:17 | [b5fbf4c24d8b](https://github.com/tldr-pages/tldr/commit/b5fbf4c24d8bfd42c352dcfdf1ea98b4fa01f367)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[Brandon Soto](mailto:brandon.soto09@gmail.com) | ansible-galaxy: update examples | 2017-09-14T06:40:12 | [eb1accac2a9d](https://github.com/tldr-pages/tldr/commit/eb1accac2a9d5aecfd883606b4175de13d39af9c)
[Brandon Soto](mailto:brandon.soto09@gmail.com) | ansible-galaxy: fix formatting errors | 2017-09-14T05:01:49 | [80d52eb2643e](https://github.com/tldr-pages/tldr/commit/80d52eb2643eb7d7669561e0a9032ccace770ba9)
[Brandon Soto](mailto:brandon.soto09@gmail.com) | ansible-galaxy: add page | 2017-09-14T04:57:24 | [7b72852a8883](https://github.com/tldr-pages/tldr/commit/7b72852a88833bb98777ca515e182137873da894)

