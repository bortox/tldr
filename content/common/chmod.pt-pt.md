---
author: ['Dario Vladović', 'FilipaDurao', 'marchersimon']
date: 1617292466
title: "chmod, TLDR Pages"
description: "chmod, Alterar as permissões de acesso a um ficheiro ou diretório."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/coreutils/chmod>.

- Dar a um [u]tilizador que possui um ficheiro o direito a e[x]ecutá-lo:

```bash
chmod u+x ficheiro
```

- Dar a um [u]tilizador direitos para le[r] e escrever ([w]) num ficheiro/diretório:

```bash
chmod u+rw ficheiro_ou_diretorio
```

- Remover direitos de execução de um [g]rupo:

```bash
chmod g-x ficheiro
```

- Dar a todos ([a]) os utilizadores o direito de le[r] e e[x]ecutar:

```bash
chmod a+rx ficheiro
```

- Dar a [o]utros (que não estão no grupo do dono do ficheiro) os mesmos direitos do [g]rupo:

```bash
chmod o=g ficheiro
```

- Remover todos os direitos dos [o]utros:

```bash
chmod o= ficheiro
```

- Mudar as permissões, recursivamente, dando ao [g]rupo e [o]utros a possibilidade de escrever ([w]):

```bash
chmod -R g+w,o+w diretorio
```
Lista de alterações feitas a esta documentação


Autor | Descrição | Formato de data ISO 8601 | Ligação a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chmod: change more information link (#5547) | 2021-03-29T22:28:18 | [db38dff0e9db](https://github.com/tldr-pages/tldr/commit/db38dff0e9db1d880e7406df340d16509470fbbb)
[FilipaDurao](mailto:32716065+FilipaDurao@users.noreply.github.com) | chmod: add Portuguese translation (#4501) * Create chmod.md * chmod/pt_PT: fix double blank line * chmod/pt_PT: really fix it Co- [...] | 2020-10-06T17:55:19 | [02d850e4c542](https://github.com/tldr-pages/tldr/commit/02d850e4c542fc6ebaef1946e27939dfca9b9b26)

