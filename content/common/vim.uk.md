---
author: ['Constantine']
date: 1635500169
title: "vim"
description: "vim, Vim (Vi IMproved), консольний текстовий редактор, надає різні режими для різних маніпуляцій над текстом."
categories: "common"
---
> Натиснувши `i` потрапляємо в режим вставки (insert mode). `<Esc>` повертає у нормальний режим (normal mode), який дозволяє користуватися командами Vim.

> Більше інформації: <https://www.vim.org>.

- Відкрити файл:

```bash
vim шлях/до/файлу
```

- Відкрити файл на визначеноу рядку:

```bash
vim +номер_рядку шлях/до/файлу
```

- Подивитися допомогу Vim:

```bash
:help<Enter>
```

- Зберегти і вийти:

```bash
:wq<Enter>
```

- Анулювати (undo) останню операцію:

```bash
u
```

- Знайти паттерн у файлі (натисніть `n`/`N` щоб перейти до наступного/попереднього збігу):

```bash
/паттерн_для_пошуку<Enter>
```

- Виконати регексп заміну в цілому файлі:

```bash
:%s/регексп_вираз/заміна/g<Enter>
```

- Показати номери рядків:

```bash
:set nu<Enter>
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Constantine](mailto:k.korobov@gmail.com) | vi, vim: add Ukrainian translation (#7251) | 2021-10-29T11:36:09 | [444e39bfb4a8](https://github.com/tldr-pages/tldr/commit/444e39bfb4a8dd5cf0f19610f1acc0a14ad1cb3f)

