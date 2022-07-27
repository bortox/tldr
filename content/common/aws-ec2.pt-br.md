---
author: ['Carlos Vieira', 'bl-ue']
date: 1610811211
title: "aws ec2, TLDR Pages"
description: "aws ec2, Inteface de linha de comando para o AWS EC2."
categories: "common"
---
> Provê capacidade computacional segura e flexível na nuvem da AWS para proporcionar um desenvolvimento e subida para produção de aplicações rapidamente.

> Mais informações: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/ec2/index.html>.

- Lista todos os comandos EC2 disponíveis:

```bash
aws ec2 help
```

- Exibe ajuda específica para um subcomando da EC2:

```bash
aws ec2 subcomando help
```

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
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages, MAINTAINERS: remove trailing whitespace at line ends (#5151) * multiple pages: remove trailing whitespace at the end [...] | 2021-01-16T16:33:31 | [96145696557f](https://github.com/tldr-pages/tldr/commit/96145696557f2ee2d55577cd8a617d5a1885d200)
[Carlos Vieira](mailto:3831408+caduvieira@users.noreply.github.com) | aws-ec2: add pt_BR translation | 2020-11-01T14:37:16 | [4e9318fc4fbd](https://github.com/tldr-pages/tldr/commit/4e9318fc4fbd1f9f63e0f79e907dca054741a986)

