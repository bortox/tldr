---
author: ['Marco Bonelli', 'marchersimon']
date: 1618756407
title: "apg"
description: "apg, Criar senhas aleatórias arbitrariamente complexas."
categories: "common"
---
> Mais informações: <https://manned.org/apg>.

- Criar senha aleatória (tamanho padrão para as senhas é 8 caracteres):

```bash
apg
```

- Criar senha com pelo menos 1 símbolo (S), 1 número (N), 1 letra maiúscula (C), 1 letra minúscula (L):

```bash
apg -M SNCL
```

- Criar uma senha com 16 caracteres:

```bash
apg -m 16
```

- Criar senha com tamanho máximo de 16 caracteres:

```bash
apg -x 16
```

- Criar uma senha que não aparece em um dicionário provido pelo usuário:

```bash
apg -r arquivo_de_dicionario
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: Axel Navarro <navarroaxel@gmail.com> Co-authored-by: bl-ue <54780737+bl- [...] | 2021-04-18T16:33:27 | [a8cbf084db1c](https://github.com/tldr-pages/tldr/commit/a8cbf084db1c27995da74db5833681eaea87dbfb)
[marchersimon](mailto:marchersimon@zohomail.eu) | apg: edit link | 2021-04-18T16:33:27 | [ec6a3682f0fe](https://github.com/tldr-pages/tldr/commit/ec6a3682f0feaea05c28b65ddac54d395b32a284)
[marchersimon](mailto:marchersimon@zohomail.eu) | apg: add link | 2021-04-18T16:33:27 | [d5cbcd6fbca3](https://github.com/tldr-pages/tldr/commit/d5cbcd6fbca3201f690a82f177faf6679349e803)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

