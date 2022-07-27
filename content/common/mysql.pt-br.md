---
author: ['Marco Bonelli']
date: 1566793410
title: "mysql, TLDR Pages"
description: "mysql, A ferramenta de linha de comando do MySQL."
categories: "common"
---
> Mais informações: <https://www.mysql.com/>.

- Conectar a um banco de dados:

```bash
mysql nome_do_banco_de_dados
```

- Conectar a um banco de dados (será solicitada a senha de acesso do usuário):

```bash
mysql -u usuário --password nome_do_banco_de_dados
```

- Conectar a um banco de dados disponível em um endereço específico:

```bash
mysql -h endereco_do_banco_de_dados nome_do_banco_de_dados
```

- Conectar a um banco de dados utilizando um socket Unix:

```bash
mysql --socket caminho/para/socket.sock
```

- Executar todos os comandos de um arquivo SQL em um banco de dados:

```bash
mysql -e "source nome_do_arquivo.sql" nome_do_banco_de_dados
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

