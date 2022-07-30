---
author: ['Victor Jacobs', 'Seth Falco', 'OrBaruk', 'gx1', 'Starbeamrainbowlabs', 'Marco Bonelli', 'bl-ue', 'hellojukay']
date: 1629050349
title: "ansible-playbook"
description: "ansible-playbook, Execute tasks defined in playbook on remote machines over SSH."
categories: "common"
---
> More information: <https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html>.

- Run tasks in playbook:

```bash
ansible-playbook playbook
```

- Run tasks in playbook with custom host inventory:

```bash
ansible-playbook playbook -i inventory_file
```

- Run tasks in playbook with extra variables defined via the command-line:

```bash
ansible-playbook playbook -e "variable1=value1 variable2=value2"
```

- Run tasks in playbook with extra variables defined in a JSON file:

```bash
ansible-playbook playbook -e "@variables.json"
```

- Run tasks in playbook for the given tags:

```bash
ansible-playbook playbook --tags tag1,tag2
```

- Run tasks in a playbook starting at a specific task:

```bash
ansible-playbook playbook --start-at task_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[hellojukay](mailto:licong@qianxin.com) | ansible-playbook: fix --tags example (#4328) | 2020-09-11T05:55:18 | [61dadb846bc3](https://github.com/tldr-pages/tldr/commit/61dadb846bc3c068f530751b32b2884a2f5bd84f)
[gx1](mailto:g.per45@gmail.com) | ansible-playbook: add start-at and tags commands (#4171) | 2020-07-17T18:58:11 | [887b7e719007](https://github.com/tldr-pages/tldr/commit/887b7e7190076d9b8ce9ef3e5b5b5642186032de)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Revert "multiple pages: add homepages" This reverts commit 347e5573036e13b360b81a3f9f1bad75cf2c2b03. | 2018-12-20T00:33:18 | [45ec3033c04f](https://github.com/tldr-pages/tldr/commit/45ec3033c04fbc67b97fa4d21e2b409b1f14a667)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages | 2018-12-20T00:29:00 | [347e5573036e](https://github.com/tldr-pages/tldr/commit/347e5573036e13b360b81a3f9f1bad75cf2c2b03)
[OrBaruk](mailto:OrBaruk@users.noreply.github.com) | ansible-playbook: fix typo | 2017-10-26T22:29:17 | [12bb6f2449bd](https://github.com/tldr-pages/tldr/commit/12bb6f2449bdaec76512384dda966f3495e0ed42)
[OrBaruk](mailto:OrBaruk@users.noreply.github.com) | ansible-playbook: add extra-vars examples | 2017-10-26T22:07:08 | [873d2102eba4](https://github.com/tldr-pages/tldr/commit/873d2102eba43a9a3e473dd44bb9680dd6962459)
[Victor Jacobs](mailto:victor.jacobs@me.com) | ansible-playbook: add page (#1257) | 2017-01-27T10:39:22 | [2b0bc0be9101](https://github.com/tldr-pages/tldr/commit/2b0bc0be91019685476b1d13c23e5da831b0f839)

