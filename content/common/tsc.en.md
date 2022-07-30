---
author: ['Waldir Pimenta', 'bl-ue']
date: 1621541621
title: "tsc"
description: "tsc, TypeScript compiler."
categories: "common"
---
> More information: <https://www.typescriptlang.org/docs/handbook/compiler-options.html>.

- Compile a TypeScript file `foobar.ts` into a JavaScript file `foobar.js`:

```bash
tsc foobar.ts
```

- Compile a TypeScript file into JavaScript using a specific target syntax (default is `ES3`):

```bash
tsc --target ES5|ES2015|ES2016|ES2017|ES2018|ESNEXT foobar.ts
```

- Compile a TypeScript file into a JavaScript file with a custom name:

```bash
tsc --outFile output.js input.ts
```

- Compile all `.ts` files of a TypeScript project defined in a `tsconfig.json` file:

```bash
tsc --build tsconfig.json
```

- Run the compiler using command-line options and arguments fetched from a text file:

```bash
tsc @args.txt
```

- Type-check multiple JavaScript files, and output only the errors:

```bash
tsc --allowJs --checkJs --noEmit src/**/*.js
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | tsc: add page (#3173) | 2019-07-07T15:25:20 | [c916836015a3](https://github.com/tldr-pages/tldr/commit/c916836015a31d8f488b6bf0e44ed9a9ef0cb99f)

