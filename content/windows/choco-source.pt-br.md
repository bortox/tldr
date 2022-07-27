---
author: ['Bruno Eduardo de Souza Medeiros', 'Axel Navarro']
date: 1620501938
title: "choco source, TLDR Pages"
description: "choco source, Gerenciar fontes para pacotes com Chocolatey."
categories: "windows"
---
> Mais informações: <https://chocolatey.org/docs/commands-source>.

- Listar fontes atualmente disponíveis:

```bash
choco source list
```

- Adicionar uma nova fonte de pacotes:

```bash
choco source add --name nome --source url_da_fonte
```

- Adicionar uma nova fonte de pacotes com credenciais:

```bash
choco source add --name nome --source url_da_fonte --user nome --password senha
```

- Adicionar uma nova fonte de pacotes com certificado do cliente:

```bash
choco source add --name nome --source url_da_fonte --cert caminho/para/certificado
```

- Habilitar uma fonte de pacotes:

```bash
choco source enable --name nome
```

- Desabilitar uma fonte de pacotes:

```bash
choco source disable --name nome
```

- Remover uma fonte de pacotes:

```bash
choco source remove --name nome
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | choco-source: normalize caminho para certificado | 2021-05-08T21:25:38 | [b385ca36298a](https://github.com/tldr-pages/tldr/commit/b385ca36298a9660147fbfb99e6747f9b9b14ba5)
[Bruno Eduardo de Souza Medeiros](mailto:50559336+brunoeduardodev@users.noreply.github.com) | choco-*: add pt_BR translation (#4868) | 2020-10-28T19:06:39 | [c105fe4d88ab](https://github.com/tldr-pages/tldr/commit/c105fe4d88ab88c28163213bd25cae1fcdfebdc6)

