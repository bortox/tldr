---
author: ['Michal', 'bl-ue', 'Guido Lena Cota']
date: 1621541621
title: "aws"
description: "aws, Oficjalne narzędzie CLI dla Amazon Web Services."
categories: "common"
---
> Wizard, SSO, Resource Autocompletion, i opcje YAML są tylko v2.

> Więcej informacji: <https://aws.amazon.com/cli>.

- Konfiguruj AWS Command-line:

```bash
aws configure wizard
```

- Konfiguruj AWS Command-line używając SSO:

```bash
aws configure sso
```

- Zobacz tekst pomocy dla polecenia AWS:

```bash
aws komenda help
```

- Uzyskaj tożsamość wywołującego (służy do rozwiązywania problemów z uprawnieniami):

```bash
aws sts get-caller-identity
```

- Wyświetla listę zasobów AWS w regionie i wyświetla w yaml:

```bash
aws dynamodb list-tables --region us-east-1 --output yaml
```

- Użyj auto prompt do pomocy z poleceniem:

```bash
aws iam create-user --cli-auto-prompt
```

- Uzyskaj interaktywnego kreatora dla zasobu AWS:

```bash
aws dynamodb wizard nowa_tabela
```

- Generuj JSON CLI Skeleton (przydatne dla infrastruktury jako kodu):

```bash
aws dynamodb update-table --generate-cli-skeleton
```
Wykaz zmian wprowadzonych do niniejszej dokumentacji


Autor | Opis. | Format daty ISO 8601 | Link do GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Michal](mailto:mich.biesiada@gmail.com) | update aws updated | 2020-04-19T14:31:16 | [703be5915e24](https://github.com/tldr-pages/tldr/commit/703be5915e248a6ec51376736e3ed0423f757e7d)
[Michal](mailto:mich.biesiada@gmail.com) | update aws updated | 2020-04-19T14:31:16 | [27591de95236](https://github.com/tldr-pages/tldr/commit/27591de952365e9f66c64ceb0b90fb69eeaec3a4)
[Michal](mailto:mich.biesiada@gmail.com) | create aws.md initial | 2020-04-19T14:31:16 | [fde541bb1ecd](https://github.com/tldr-pages/tldr/commit/fde541bb1ecdde7aa2aabbdb56a0dca1e39b1e22)

