---
author: ['Ilya Pantsyr']
date: 1650222520
title: "gist"
description: "gist, Завантажує код у https://gist.github.com."
categories: "common"
---
> Більше інформації: <https://github.com/defunkt/gist>.

- Увійти в gist на цьому комп'ютері:

```bash
gist --login
```

- Створити gist з будь-якої кількості текстових файлів:

```bash
gist ім'я_файлу.txt ім'я_файлу2.txt
```

- Створити приватний gist з описом:

```bash
gist --private --description "Змістовний опис" ім'я_файлу.txt 
```

- Прочитати контент з stdin і створити gist з цього:

```bash
echo "привіт світ" | gist
```

- Перелічити свої публічні та приватні gist:

```bash
gist --list
```

- Перелічити всі публічні gist будь-якого користувача:

```bash
gist --list ім'я_користувача
```

- Оновити gist за допомогою ID з URL:

```bash
gist --update GIST_ID ім'я_файлу.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ilya Pantsyr](mailto:panilyau@gmail.com) | gist, git-abort, openssl: add Ukrainian translation (#8032) | 2022-04-17T21:08:40 | [e69ebee138ee](https://github.com/tldr-pages/tldr/commit/e69ebee138ee1f93639e8b32203fe571655cdf27)

