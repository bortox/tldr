---
author: ['Lucas Gabriel Schneider', 'marchersimon', 'Michal']
date: 1633112881
title: "sudo, TLDR Pages"
description: "sudo, Wykonuje pojedyncze polecenie jako superuser lub inny użytkownik."
categories: "common"
---
> Więcej informacji: <https://www.sudo.ws/sudo.html>.

- Uruchom polecenie jako superuser:

```bash
sudo less /var/log/syslog
```

- Edytuj plik jako superuser w domyślnym edytorze:

```bash
sudo -e /etc/fstab
```

- Uruchom polecenie jako inny użytkownik i/lub grupa:

```bash
sudo -u uzytkownik -g grupa id -a
```

- Powtórz ostatnie polecenie poprzedzone `sudo` (tylko w `bash`, `zsh`, etc.):

```bash
sudo !!
```

- Uruchom domyślną powłokę z uprawnieniami superuser:

```bash
sudo -i
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Michal](mailto:mich.biesiada@gmail.com) | update sudo updated | 2020-04-19T14:31:16 | [b9711f27c891](https://github.com/tldr-pages/tldr/commit/b9711f27c891f98807d55f9047d8e7a824779b69)
[Michal](mailto:mich.biesiada@gmail.com) | update sudo updated | 2020-04-19T14:31:16 | [92a1eb580e0c](https://github.com/tldr-pages/tldr/commit/92a1eb580e0c12ce2caa184cb84c1da14b5be91a)
[Michal](mailto:mich.biesiada@gmail.com) | create sudo.md initial | 2020-04-19T14:31:16 | [f1623f42ee2c](https://github.com/tldr-pages/tldr/commit/f1623f42ee2ce4bbb75b84bd0c6f097b5cfe7b07)

