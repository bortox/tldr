---
author: ['Julia Furst Morgado']
date: 1658169896
title: "agate, TLDR Pages"
description: "agate, Um simples servidor para o protocolo de internet Gemini."
categories: "common"
---
> Mais informações: <https://github.com/mbrubeck/agate>.

- Executa e gera uma chave privada e um certificado:

```bash
agate --content caminho/para/conteudo/ --addr [::]:1965 --addr 0.0.0.0:1965 --hostname example.com --lang en-US
```

- Executa o servidor:

```bash
agate caminho/para/arquivo
```

- Exibe opções de ajuda:

```bash
agate -h
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Julia Furst Morgado](mailto:52685951+juliafmorgado@users.noreply.github.com) | agate: add pt_BR translation (#8198) | 2022-07-18T20:44:56 | [521f2f7f6b27](https://github.com/tldr-pages/tldr/commit/521f2f7f6b27fa0cc266722f7d9a052db433e7ea)

