---
author: ['bl-ue', 'K.B.Dharun Krishna', 'Carlos Vieira']
date: 1660626861
title: "aws ec2"
description: "aws ec2, Inteface de linha de comando para o AWS EC2."
categories: "common"
---
> Provê capacidade computacional segura e flexível na nuvem da AWS para proporcionar um desenvolvimento e subida para produção de aplicações rapidamente.

> Mais informações: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/ec2/index.html>.

- Exibe informações sobre uma insntância específica:

```bash
aws ec2 describe-instances --instance-ids id_da_instância
```

- Exibe informações sobre todas as instâncias:

```bash
aws ec2 describe-instances
```

- Exibe informações sobre todos os volumes EC2:

```bash
aws ec2 describe-volumes
```

- Deleta um volume EC2:

```bash
aws ec2 delete-volume --volume-id id_do_volume
```

- Cria um snapshot de um volume EC2:

```bash
aws ec2 create-snapshot --volume-id id_do_volume
```

- Lista as AMIs (Imagem de Máquina da Amazon) disponíveis:

```bash
aws ec2 describe-images
```

- Lista todos os comandos EC2 disponíveis:

```bash
aws ec2 help
```

- Exibe ajuda específica para um subcomando da EC2:

```bash
aws ec2 subcomando help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | aws-ec2: Reorder commands in page (#8355) * aws-ec2: Update page * aws-ec2: update page(de) * aws-ec2:Update page(fr) * aws-ec2:Update [...] | 2022-08-16T07:14:21 | [42161e882c98](https://github.com/tldr-pages/tldr/commit/42161e882c98627f61410cf628d2615b46aefb4f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[Carlos Vieira](mailto:3831408+caduvieira@users.noreply.github.com) | aws-ec2: add pt_BR translation | 2020-11-01T14:37:16 | [4e9318fc4fbd](https://github.com/tldr-pages/tldr/commit/4e9318fc4fbd1f9f63e0f79e907dca054741a986)

