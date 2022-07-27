---
author: ['lincc', 'Rui Alves']
date: 1632422063
title: "lsof, TLDR Pages"
description: "lsof, Lista arquivos abertos e os seus processos correspondentes."
categories: "common"
---
> Nota: Privilégios de administrador (ou sudo) são necessários para listar arquivos abertos por outros.

> Mais informações: <https://manned.org/lsof>.

- Localizar os processos que têm um certo arquivo aberto:

```bash
lsof caminho/para/arquivo
```

- Localizar o processo que abriu uma porta de internet local:

```bash
lsof -i :porta
```

- Mostrar o ID (PID) do processo que abriu um arquivo especificado:

```bash
lsof -t caminho/para/arquivo
```

- Listar arquivos abertos por um certo usuário:

```bash
lsof -u nome_usuario
```

- Listar arquivos abertos por um certo comando ou processo:

```bash
lsof -c nome_processo_ou_comando
```

- Listar arquivos abertos por um certo processo, dado o seu PID:

```bash
lsof -p PID
```

- Listar arquivos abertos em um diretório:

```bash
lsof +D caminho/para/diretório
```

- Encontrar o processo que está ouvindo uma porta de TCP local:

```bash
lsof -iTCP:porta -sTCP:LISTEN
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | common/l*: add more information link (#6577) | 2021-09-23T20:34:23 | [35d3601e388a](https://github.com/tldr-pages/tldr/commit/35d3601e388ad4b54affea092d6dd4f0a8be37d2)
[Rui Alves](mailto:up201606746@fe.up.pt) | lsof: add pt_BR translation (#3387) | 2019-10-19T15:41:29 | [7a5e74585cb9](https://github.com/tldr-pages/tldr/commit/7a5e74585cb9aa9f530d861e2017fe98fc59f8d2)

