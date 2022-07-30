---
author: ['Michal']
date: 1587299476
title: "mysql"
description: "mysql, Narzędzie wiersza polecenia MySQL."
categories: "common"
---
> Więcej informacji: <https://www.mysql.com/>.

- Połącz z bazą danych:

```bash
mysql nazwa_bazydanych
```

- Połącz się z bazą danych, użytkownik zostanie poproszony o podanie hasła:

```bash
mysql -u uzytkownik --password nazwa_bazydanych
```

- Połącz się z bazą danych na innym hoście:

```bash
mysql -h host_bazydanych nazwa_bazydanych
```

- Połącz się z bazą danych przez gniazdo Unix:

```bash
mysql --socket sciezka/do/socket.sock
```

- Wykonuj instrukcje SQL w pliku skryptu (plik wsadowy):

```bash
mysql -e "source nazwapliku.sql" nazwa_bazydanych
```

- Przywróć bazę danych z kopii zapasowej (użytkownik zostanie poproszony o podanie hasła):

```bash
mysql --user uzytkownik --password nazwa_bazydanych < sciezka/do/backup.sql
```

- Przywróć wszystkie bazy danych z kopii zapasowej (użytkownik zostanie poproszony o podanie hasła):

```bash
mysql --user uzytkownik --password < sciezka/do/backup.sql
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[Michal](mailto:mich.biesiada@gmail.com) | update mysql updated | 2020-04-19T14:31:16 | [359886d56fe6](https://github.com/tldr-pages/tldr/commit/359886d56fe6ca106a23efce6b4bcf359147ba05)
[Michal](mailto:mich.biesiada@gmail.com) | update mysql updated | 2020-04-19T14:31:16 | [81e5a1e49dbb](https://github.com/tldr-pages/tldr/commit/81e5a1e49dbb5012c57fa1697faa631ddb0daf9d)
[Michal](mailto:mich.biesiada@gmail.com) | create mysql.md initial | 2020-04-19T14:31:16 | [f1c1568fb55b](https://github.com/tldr-pages/tldr/commit/f1c1568fb55b6f13a09f1fbfb79cf7231b370084)

