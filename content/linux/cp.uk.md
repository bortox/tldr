---
author: ['Ilya Pantsyr']
date: 1650106744
title: "cp"
description: "cp, Скопіювати файли і папки."
categories: "linux"
---
> Більше інформації: <https://www.gnu.org/software/coreutils/cp>.

- Скопіювати файл в інше місце:

```bash
cp шлях/до/файлу_який_скопіювати.ext шлях/до/файлу_в_який_скопіювати.ext
```

- Скопіювати файл в іншу папку, зберугіючи назву файлу:

```bash
cp шлях/до/файлу_який_скопіювати.ext шлях/до/папки_в_яку_скопіювати
```

- Рекурсивно скопіювати вміст папки до іншого місця (якщо місце призначення існує, папка скопіюється всередину нього):

```bash
cp -r шлях/до/файлу_який_скопіювати шлях/до/папки_в_яку_скопіювати
```

- Скопіювати папку рекурсивно у докладнішому режимі (показує файли у міру їх копіювання):

```bash
cp -vr шлях/до/папки_яку_спопіювати шлях/до/папки_в_яку_скопіювати
```

- Скопіювати текстові файли в інше місце в інтерактивному режимі (запитує користувача перед перезаписом):

```bash
cp -i *.txt шлях/до/папки_в_яку_скопіювати
```

- Зберігає символічні посилання(symbolic link) перед копіюванням:

```bash
cp -L посилання шлях/до/папки_в_яку_скопіювати
```

- Використовує повний шлях файлу який потрібно скопіювати, створюючи будь-які відсутні проміжні папки під час копіювання:

```bash
cp --parents повний/шлях/до/файлу шлях/до/бажаного_файлу
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ilya Pantsyr](mailto:panilyau@gmail.com) | cp: add Ukrainian translation (#8026) * cp: add Ukrainian translation * cp: remove trailing whitespace * cp: add one more example in [...] | 2022-04-16T12:59:04 | [dfd1ada45ed1](https://github.com/tldr-pages/tldr/commit/dfd1ada45ed1e38db36d0ecc6cb4cf31367ed71d)

