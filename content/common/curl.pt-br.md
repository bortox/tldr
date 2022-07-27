---
author: ['Nicolas Kosinski', 'bl-ue', 'Waldir Pimenta', 'Rui Alves']
date: 1620121027
title: "curl, TLDR Pages"
description: "curl, Transfere dados entre o computador local e um servidor remoto."
categories: "common"
---
> Suporta a maioria dos protocolos de comunicação, incluindo HTTP, FTP e POP3.

> Mais informações: <https://curl.se>.

- Descarregar os conteúdos de um URL para um arquivo:

```bash
curl http://example.com --output arquivo
```

- Descarregar um arquivo, gravando o resultado sob o nome do arquivo indicado pelo URL:

```bash
curl --remote-name http://example.com/arquivo
```

- Descarregar um arquivo, seguindo redirecionamentos e automaticamente continuando transferências idênticas que tenham sido interrompidas:

```bash
curl --remote-name --location --continue-at - http://example.com/arquivo
```

- Enviar dados codificados por formulário (pedido POST do tipo `application/x-www-form-urlencoded`):

```bash
curl --data 'nome=maria' http://example.com/formulario
```

- Enviar um pedido com um cabeçalho adicional, usando um método HTTP personalizado:

```bash
curl --header 'X-Meu-Cabecalho: 123' --request PUT http://example.com
```

- Enviar dados no formato JSON, especificando o cabeçalho de tipo de conteúdo (content-type) apropriado:

```bash
curl --data '{"nome":"maria"}' --header 'Content-Type: application/json' http://example.com/usuarios/123
```

- Passar ao pedido o nome de usuário e senha para autenticação no servidor:

```bash
curl -u usuario:senha http://example.com
```

- Passar ao pedido o certificado do cliente e a chave para um recurso, omitindo a validação do certificado:

```bash
curl --cert client.pem --key key.pem --insecure https://example.com
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | curl: use long arguments (#5872) | 2021-05-04T11:37:07 | [69f02b651045](https://github.com/tldr-pages/tldr/commit/69f02b65104530e9f5d1d32a9528f2d3803050e0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | curl: update to new 'more information' link (#5254) | 2021-02-07T21:27:41 | [ca9ba675cea1](https://github.com/tldr-pages/tldr/commit/ca9ba675cea1e8accb6121c8c52c4bb273df5163)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | pt_BR/curl: small tweaks to the main description (#4236) | 2020-08-02T20:46:52 | [50b223d0f1dc](https://github.com/tldr-pages/tldr/commit/50b223d0f1dcce5b7c5f33c82ef7e82846415325)
[Rui Alves](mailto:up201606746@fe.up.pt) | curl: add pt_BR translation (#3384) | 2019-10-19T15:41:42 | [67619fc95732](https://github.com/tldr-pages/tldr/commit/67619fc957325df81d1644f43bb4ad55525eeec3)

