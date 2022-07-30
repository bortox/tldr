---
author: ['Lucas Gabriel Schneider', 'Adam Herst', 'Darius Karel', 'Guido Lena Cota', 'Starbeamrainbowlabs', 'Marco Bonelli', 'marchersimon']
date: 1631521281
title: "ansible"
description: "ansible, Manage groups of computers remotely over SSH. (use the `/etc/ansible/hosts` file to add new groups/hosts)."
categories: "common"
---
> Some subcommands such as `ansible galaxy` have their own usage documentation.

> More information: <https://www.ansible.com/>.

- List hosts belonging to a group:

```bash
ansible group --list-hosts
```

- Ping a group of hosts by invoking the ping module:

```bash
ansible group -m ping
```

- Display facts about a group of hosts by invoking the setup module:

```bash
ansible group -m setup
```

- Execute a command on a group of hosts by invoking command module with arguments:

```bash
ansible group -m command -a 'my_command'
```

- Execute a command with administrative privileges:

```bash
ansible group --become --ask-become-pass -m command -a 'my_command'
```

- Execute a command using a custom inventory file:

```bash
ansible group -i inventory_file -m command -a 'my_command'
```

- List the groups in an inventory:

```bash
ansible localhost -m debug -a 'var=groups.keys()'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Adam Herst](mailto:adamherst@adamherst.com) | ansible: add list groups in an inventory example (#5755) | 2021-04-15T20:30:12 | [f72f348a0368](https://github.com/tldr-pages/tldr/commit/f72f348a0368676b52b3d5ccad4bcb70b1805343)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mass change: apply snake case to tokens (#2518) | 2018-10-29T12:14:25 | [18370557b25e](https://github.com/tldr-pages/tldr/commit/18370557b25e5340d9ee5cfeee346ce8fcb4ef95)
[Darius Karel](mailto:me@dikarel.com) | ansible: add page (#1153) | 2016-11-23T12:29:38 | [57d6e2e91e6b](https://github.com/tldr-pages/tldr/commit/57d6e2e91e6bb12b50f96c712f8d8a99864ab56b)

