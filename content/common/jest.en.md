---
author: ['Alex Hunt', 'Waldir Pimenta', 'Gary King', 'pxgamer', 'marchersimon']
date: 1620637392
title: "jest"
description: "jest, A zero-configuration JavaScript testing platform."
categories: "common"
---
> More information: <https://jestjs.io>.

- Run all available tests:

```bash
jest
```

- Run the test suites from the given files:

```bash
jest path/to/file1 path/to/file2
```

- Run the test suites from files within the current and subdirectories, whose paths match the given regular expression:

```bash
jest regular_expression1 regular_expression2
```

- Run the tests whose names match the given regular expression:

```bash
jest --testNamePattern regular_expression
```

- Run test suites related to a given source file:

```bash
jest --findRelatedTests path/to/source_file.js
```

- Run test suites related to all uncommitted files:

```bash
jest --onlyChanged
```

- Watch files for changes and automatically re-run related tests:

```bash
jest --watch
```

- Show help:

```bash
jest --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | jest: improve page and add new example (#3527) - Tweak descriptions for extra clarity - Adjust tokens in second example to illustrate [...] | 2019-11-05T02:41:20 | [dfed39c22cb7](https://github.com/tldr-pages/tldr/commit/dfed39c22cb70c73d09254bf82f82ce1c7342f54)
[Gary King](mailto:garyking@gmail.com) | jest: use the long name of commands | 2019-09-09T05:27:20 | [02ba9c170f51](https://github.com/tldr-pages/tldr/commit/02ba9c170f51daaf06d256e44aa7ceb005d18de7)
[Gary King](mailto:garyking@gmail.com) | jest: add a command for running tests from files | 2019-09-09T05:27:20 | [b55af7395762](https://github.com/tldr-pages/tldr/commit/b55af73957626ad8b95c0f22aef9bff2c292a38a)
[Gary King](mailto:garyking@gmail.com) | jest: use the short version of command to be consistent with the others on this page | 2019-09-09T05:27:20 | [5582d50b77a9](https://github.com/tldr-pages/tldr/commit/5582d50b77a92a45e91229b6eb406e3c41fdd2e0)
[Gary King](mailto:garyking@gmail.com) | jest: copyedit a few descriptions | 2019-09-09T05:27:20 | [6dabaeac102e](https://github.com/tldr-pages/tldr/commit/6dabaeac102e264d24a99d9db9f92b8b55b40dc3)
[pxgamer](mailto:owzie123@gmail.com) | jest: add link to homepage | 2019-06-06T04:42:48 | [5571d6ed733f](https://github.com/tldr-pages/tldr/commit/5571d6ed733f151a008c7936a8ddf6100e50aaf5)
[Alex Hunt](mailto:hello@alexhunt.io) | jest: add page (#2528) | 2018-11-20T22:22:00 | [0c6cca1d983e](https://github.com/tldr-pages/tldr/commit/0c6cca1d983eea2ab56a8b4d7af842068bab1b4f)

