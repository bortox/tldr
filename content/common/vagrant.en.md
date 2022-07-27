---
author: ['Owen Voke', 'Marco Bonelli', 'Ruben Vereecken', 'hellojukay', 'Igor Shubovych', 'Larry Lu', 'Mateusz Konieczny']
date: 1645626799
title: "vagrant, TLDR Pages"
description: "vagrant, Manage lightweight, reproducible, and portable development environments."
categories: "common"
---
> More information: <https://www.vagrantup.com>.

- Create Vagrantfile in current directory with the base Vagrant box:

```bash
vagrant init
```

- Create Vagrantfile with the Ubuntu 20.04 (Focal Fossa) box from HashiCorp Atlas:

```bash
vagrant init ubuntu/focal64
```

- Start and provision the vagrant environment:

```bash
vagrant up
```

- Suspend the machine:

```bash
vagrant suspend
```

- Halt the machine:

```bash
vagrant halt
```

- Connect to machine via SSH:

```bash
vagrant ssh
```

- Output the SSH configuration file of the running Vagrant machine:

```bash
vagrant ssh-config
```

- List all local boxes:

```bash
vagrant box list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[hellojukay](mailto:hellojukay@163.com) | vagrant: add box list example (#7810) | 2022-02-23T15:33:19 | [1d72e2f253d5](https://github.com/tldr-pages/tldr/commit/1d72e2f253d599b57d5f88cb80d649ffe8b124b2)
[Mateusz Konieczny](mailto:matkoniecz@gmail.com) | vagrant: update init ubuntu example (#7682) | 2022-01-19T15:08:03 | [51bad90afa75](https://github.com/tldr-pages/tldr/commit/51bad90afa75248a00cbc4e071df4d15a144947b)
[hellojukay](mailto:licong@qianxin.com) | mdbook: add page (#4351) | 2020-09-25T08:35:24 | [4538547a6f8e](https://github.com/tldr-pages/tldr/commit/4538547a6f8e0d98b338bede68db41efe2486a14)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Larry Lu](mailto:pudding850806@gmail.com) | vagrant: add halt example (#2961) | 2019-04-30T09:52:55 | [49e97b7879b6](https://github.com/tldr-pages/tldr/commit/49e97b7879b6c18073ba0475cad954cc3106a8be)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | vagrant: add page | 2015-12-31T03:31:15 | [44eb0501023a](https://github.com/tldr-pages/tldr/commit/44eb0501023a5eb2f2263089e2406332faf35c0e)

