---
author: ['Marco Bonelli', 'Rui Alves']
date: 1572006427
title: "mongo, TLDR Pages"
description: "mongo, Cliente shell interativo de MongoDB."
categories: "common"
---
> Mais informações: <https://docs.mongodb.com/manual/reference/program/mongo>.

- Conectar a uma base de dados:

```bash
mongo base_de_dados
```

- Conectar a uma base de dados em um host e porta específicos:

```bash
mongo --host host --port porta base_de_dados
```

- Conectar a uma base de dados com um usuário específico, uma senha será pedida ao usuário:

```bash
mongo --username usuário base_de_dados --password
```

- Avaliar JavaScript na base de dados:

```bash
mongo --eval 'JSON.stringify(db.foo.findOne())' base_de_dados
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | multiple pages (pt_BR): add missing trailing newline. | 2019-10-25T14:27:07 | [0d3209adbbbf](https://github.com/tldr-pages/tldr/commit/0d3209adbbbf41b9672a1bed97c13e7081c269f2)
[Rui Alves](mailto:up201606746@fe.up.pt) | mongo: add pt_BR translation (#3398) | 2019-10-18T04:33:57 | [a9e0602d7478](https://github.com/tldr-pages/tldr/commit/a9e0602d74783f0bce15dc21ebd2448d048618c6)

