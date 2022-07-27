---
author: ['Sadeed', 'Starbeamrainbowlabs']
date: 1633438245
title: "monop, TLDR Pages"
description: "monop, Finds and displays signatures of Types and methods inside .NET assemblies."
categories: "common"
---
> More information: <https://manned.org/monop>.

- Show the structure of a Type built-in of the .NET Framework:

```bash
monop System.String
```

- List the types in an assembly:

```bash
monop -r:path/to/assembly.exe
```

- Show the structure of a Type in a specific assembly:

```bash
monop -r:path/to/assembly.dll Namespace.Path.To.Type
```

- Only show members defined in the specified Type:

```bash
monop -r:path/to/assembly.dll --only-declared Namespace.Path.To.Type
```

- Show private members:

```bash
monop -r:path/to/assembly.dll --private Namespace.Path.To.Type
```

- Hide obsolete members:

```bash
monop -r:path/to/assembly.dll --filter-obsolete Namespace.Path.To.Type
```

- List the other assemblies that a specified assembly references:

```bash
monop -r:path/to/assembly.dll --refs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | mail, mailx, mesg, mmv, monop, most, mscore: add link (#6795) | 2021-10-05T14:50:45 | [696b11611fa5](https://github.com/tldr-pages/tldr/commit/696b11611fa5c0ebd61d71d470fc2cd34b700f08)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | monop: add page (#2568) | 2018-11-21T18:09:00 | [d1fa3ec7f16c](https://github.com/tldr-pages/tldr/commit/d1fa3ec7f16ce74e352279fb9a04eec7bbce5bdd)

