---
author: ['Marco Bonelli']
date: 1566793410
title: "mysqldump, TLDR Pages"
description: "mysqldump, Realizar e restaurar backups no MySQL."
categories: "common"
---
> Mais informações: <https://dev.mysql.com/doc/refman/en/mysqldump.html>.

- Criar o backup do banco de dados em arquivo de saída (será solicitada a senha de acesso do usuário):

```bash
mysqldump -u usuário --password nome_do_banco_de_dados -r arquivo_de_saida.sql
```

- Restaurar o conteúdo contido no arquivo de backup em banco de dados específico (será solicitada a senha de acesso do usuário):

```bash
mysql -u usuário --password -e "source arquivo_de_backup.sql" nome_do_banco_de_dados
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

