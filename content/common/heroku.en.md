---
author: ['Waldir Pimenta', 'bl-ue', 'Marco Bonelli', 'Yash Sharma', 'Lucas Gabriel Schneider', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "heroku, TLDR Pages"
description: "heroku, Create and manage Heroku apps from the command-line."
categories: "common"
---
> More information: <https://www.heroku.com/>.

- Log in to your Heroku account:

```bash
heroku login
```

- Create a Heroku app:

```bash
heroku create
```

- Show logs for an app:

```bash
heroku logs --app app_name
```

- Run a one-off process inside a dyno (Heroku virtual machine):

```bash
heroku run process_name --app app_name
```

- List dynos (Heroku virtual machines) for an app:

```bash
heroku ps --app app_name
```

- Permanently destroy an app:

```bash
heroku destroy --app app_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3025) | 2019-05-14T18:06:07 | [5514f773e2df](https://github.com/tldr-pages/tldr/commit/5514f773e2dfcd02ab6bc87c7e02fa8f7fbe2f25)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | heroku: capitalize "Heroku" in descriptions | 2016-10-16T12:56:22 | [d04986077317](https://github.com/tldr-pages/tldr/commit/d049860773170dfa13536d2026ee030193f6558b)
[Yash Sharma](mailto:yasharmaster@gmail.com) | heroku: add page (#1112) | 2016-10-16T12:55:03 | [c09702e56408](https://github.com/tldr-pages/tldr/commit/c09702e5640890e985b4046162974e45e2893f08)

