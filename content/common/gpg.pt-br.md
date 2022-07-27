---
author: ['Lucas Gabriel Schneider', 'caduvieira']
date: 1612112718
title: "gpg, TLDR Pages"
description: "gpg, GNU Privacy Guard."
categories: "common"
---
> Mais informações: <https://gnupg.org>.

- Assina doc.txt, sem criptografá-lo (cria um arquivo de saída doc.txt.asc):

```bash
gpg --clearsign doc.txt
```

- Criptografa doc.txt para alice@example.com (cria um arquivo de saída `doc.txt.gpg`):

```bash
gpg --encrypt --recipient alice@example.com doc.txt
```

- Criptografa doc.txt apenas com uma senha simétrica (cria um arquivo de sadída `doc.txt.gpg`):

```bash
gpg --symmetric doc.txt
```

- Descriptografa doc.txt.gpg (envia saída para stdout):

```bash
gpg --decrypt doc.txt.gpg
```

- Importa uma chave pública:

```bash
gpg --import public.gpg
```

- Exporta a chave pública da alice@example.com (envia saída para stdout):

```bash
gpg --export --armor alice@example.com
```

- Exporta chave privada da alice@example.com (envia saída para stdout):

```bash
gpg --export-secret-keys --armor alice@example.com
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[caduvieira](mailto:edu.carlos.vieira@gmail.com) | gpg: add pt_BR translation (#4713) | 2020-10-19T20:34:33 | [3d14de3192dd](https://github.com/tldr-pages/tldr/commit/3d14de3192dd4bd2af588453471045375234d0d4)

