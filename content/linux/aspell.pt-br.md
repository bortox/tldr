---
author: ['Marco Bonelli', 'Stig124']
date: 1625841955
title: "aspell, TLDR Pages"
description: "aspell, Verificador ortográfico interativo."
categories: "linux"
---
> Mais informações: <http://aspell.net/>.

- Verificar a ortografia do texto de um arquivo:

```bash
aspell check arquivo
```

- Exibir as palavras escritas incorretamente no terminal:

```bash
cat arquivo | aspell list
```

- Exibir os dicionários disponíveis:

```bash
aspell dicts
```

- Executar aspell utilizando uma língua diferente (informe o código ISO 639 da língua):

```bash
aspell --lang=cs
```

- Exibir os erros ortográficos no terminal e ignorando as palavras da lista pessoal:

```bash
cat arquivo | aspell --personal=lista_pessoal.pws list
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

