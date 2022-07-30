---
author: ['Gabriel Rodrigues']
date: 1633574036
title: "age"
description: "age, Uma simples, moderna e segura ferramenta de criptografia de arquivos."
categories: "common"
---
> Mais informações: <https://age-encryption.org>.

- Gera um arquivo criptografado que pode ser descriptografado com uma frase-chave:

```bash
age --passphrase --output caminho/para/arquivo_criptografado caminho/para/arquivo_descriptografado
```

- Gera um par de chaves, salvando a chave privada em um arquivo não criptografado e imprimindo a chave pública para stdout:

```bash
age-keygen --output caminho/para/arquivo
```

- Criptografa arquivo com uma ou mais chaves públicas que são inseridas como literais:

```bash
age --recipient chave_pública_1 --recipient chave_pública_2 caminho/para/arquivo_descriptografado --output caminho/para/arquivo_criptografado
```

- Criptografa arquivo com uma ou mais chaves públicas que são especificadas no arquivo do destinatário:

```bash
age --recipients-file caminho/para/arquivo_destinatário caminho/para/arquivo_descriptografado --output caminho/para/arquivo_criptografado
```

- Descriptografa um arquivo com uma frase-chave:

```bash
age --decrypt --output caminho/para/arquivo_descriptografado caminho/para/arquivo_criptografado
```

- Descriptografa um arquivo com um arquivo chave privada:

```bash
age --decrypt --identity caminho/para/arquivo_chave_privada --output caminho/para/arquivo_descriptografado caminho/para/arquivo_criptografado
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gabriel Rodrigues](mailto:78451370+gabxyz@users.noreply.github.com) | age: add pt_BR translation (#6841) | 2021-10-07T04:33:56 | [60f804c060f9](https://github.com/tldr-pages/tldr/commit/60f804c060f9ca02b98f480e4769d33652aae803)

