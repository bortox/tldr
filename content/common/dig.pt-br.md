---
author: ['Jonathan Reyes', 'larissa maruyama']
date: 1643311827
title: "dig, TLDR Pages"
description: "dig, Utilitário de pesquisa de DNS."
categories: "common"
---
> Mais informações: <https://manned.org/dig>.

- Pesquisa o(s) IP(s) associados a um hostname (Registros A):

```bash
dig +short exemplo.com
```

- Obtém uma resposta detalhada para um determinado domínio (Registros A):

```bash
dig +noall +answer exemplo.com
```

- Consulta um tipo de registro DNS específico associado a um nome de domínio fornecido:

```bash
dig +short exemplo.com A|MX|TXT|CNAME|NS
```

- Obtém todos os tipos de registros para um nome de domínio fornecido:

```bash
dig exemplo.com ANY
```

- Especifica um servidor DNS alternativo para consultar:

```bash
dig @8.8.8.8 exemplo.com
```

- Performa uma busca reversa de DNS em um endereço de IP (Registro PTR):

```bash
dig -x 8.8.8.8
```

- Encontra servidores de nomes autorizados para a região e exibe os registros SOA:

```bash
dig +nssearch exemplo.com
```

- Performa consultas iterativas e exibe o caminho de ratreio completo para resolver um nome de domínio:

```bash
dig +trace exemplo.com
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Jonathan Reyes](mailto:jreyes33@users.noreply.github.com) | dig: fix more information link (#7724) | 2022-01-27T20:30:27 | [cbd3214b25ef](https://github.com/tldr-pages/tldr/commit/cbd3214b25ef91e2590438cc9669c02f28720ce8)
[larissa maruyama](mailto:54145084+snorlara@users.noreply.github.com) | dig: add pt_BR translation (#7025) | 2021-10-25T23:35:39 | [312608d95ab5](https://github.com/tldr-pages/tldr/commit/312608d95ab5d156afc222c5901058e5cb30f0c0)

