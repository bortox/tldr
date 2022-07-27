---
author: ['Jean-Michel Fayard', 'Marco Bonelli', 'pxgamer', 'marchersimon']
date: 1626166788
title: "swagger-codegen, TLDR Pages"
description: "swagger-codegen, Generate code and documentation for your REST api from a OpenAPI/swagger definition."
categories: "common"
---
> More information: <https://github.com/swagger-api/swagger-codegen>.

- Generate documentation and code from an OpenAPI/swagger file:

```bash
swagger-codegen generate -i swagger_file -l language
```

- Generate Java code using the library retrofit2 and the option useRxJava2:

```bash
swagger-codegen generate -i http://petstore.swagger.io/v2/swagger.json -l java --library retrofit2 -DuseRxJava2=true
```

- List available languages:

```bash
swagger-codegen langs
```

- Display help options for the generate command:

```bash
swagger-codegen help generate
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace `java` with `Java` and `c++` with `C++` (#6224) | 2021-07-13T10:59:48 | [b615ea1e3495](https://github.com/tldr-pages/tldr/commit/b615ea1e34951c855e72470b73522ed0e0963d87)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | swagger-codegen: add link to homepage | 2019-05-14T19:58:59 | [e712541fe009](https://github.com/tldr-pages/tldr/commit/e712541fe0096212a98a55726065a7034949b9f6)
[Jean-Michel Fayard](mailto:jmfayard@gmail.com) | swagger-codegen: add page (#1727) | 2017-12-05T07:32:11 | [1c17163ab965](https://github.com/tldr-pages/tldr/commit/1c17163ab96538ec5531b3de1224eeedc212eb8e)

