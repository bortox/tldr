---
author: ['Schneider', 'Marco Bonelli', 'Martin Caarels', 'Guido Lena Cota', 'bl-ue', 'marchersimon']
date: 1621541621
title: "bosh, TLDR Pages"
description: "bosh, Command-line tool to deploy and manage the bosh director."
categories: "common"
---
> More information: <https://bosh.io/docs/cli-v2/>.

- Create local alias for director:

```bash
bosh alias-env environment_name -e ip_address|url --ca-cert ca_certificate
```

- List environments:

```bash
bosh environments
```

- Log in to the director:

```bash
bosh login -e environment 
```

- List deployments:

```bash
bosh -e environment deployments
```

- List environment virtual machines:

```bash
bosh -e environment vms -d deployment
```

- Ssh into virtual machine:

```bash
bosh -e environment ssh virtual_machine -d deployment
```

- Upload stemcell:

```bash
bosh -e environment upload-stemcell stemcell_file|url
```

- Show current cloud config:

```bash
bosh -e environment cloud-config
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | bosh.md: add homepage | 2019-04-12T14:41:22 | [ea3a308f18f9](https://github.com/tldr-pages/tldr/commit/ea3a308f18f96872bc6714d93bd7a1c0868846b0)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mass change: apply snake case to tokens (#2518) | 2018-10-29T12:14:25 | [18370557b25e](https://github.com/tldr-pages/tldr/commit/18370557b25e5340d9ee5cfeee346ce8fcb4ef95)
[Martin Caarels](mailto:martyca@users.noreply.github.com) | bosh: add page (#1575) | 2017-10-25T21:30:06 | [359252f1cec3](https://github.com/tldr-pages/tldr/commit/359252f1cec307e4d3938ea170f04b1ca8233d07)

