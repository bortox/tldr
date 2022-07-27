---
author: ['Gabriel Rodrigues']
date: 1634005028
title: "ftp, TLDR Pages"
description: "ftp, Ferramentas para interagir com um servidor via Protocolo de Transferência de Arquivos."
categories: "common"
---
> Mais informações: <https://manned.org/ftp>.

- Conecta-se a um servidor FTP:

```bash
ftp ftp.exemplo.com
```

- Alterna para o modo de transferência binária (gráficos, arquivos compactados, etc):

```bash
binary
```

- Transfere vários arquivos sem solicitar confirmação em cada arquivo:

```bash
prompt off
```

- Baixa vários arquivos (expressão glob):

```bash
mget *.png
```

- Carrega vários arquivos (expressão glob):

```bash
mput *.zip
```

- Exclui vários arquivos no servidor remoto:

```bash
mdelete *.txt
```

- Renomeia um arquivo no servidor remoto:

```bash
rename nome_do_arquivo_original nome_do_novo_arquivo
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Gabriel Rodrigues](mailto:gabrxzvski@gmail.com) | ftp: add pt_BR translation | 2021-10-12T04:17:08 | [1e0df0adf949](https://github.com/tldr-pages/tldr/commit/1e0df0adf94967e1b24cc7f906d32ab2038d9e9d)

