---
author: ['Marco Bonelli', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "chgrp, TLDR Pages"
description: "chgrp, Cambia il gruppo proprietario di file e directory."
categories: "common"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/chgrp>.

- Cambia il gruppo proprietario di un file/directory:

```bash
chgrp gruppo percorso/al/file
```

- Cambia ricorsivamente il gruppo proprietario di una directory e dei suoi contenuti:

```bash
chgrp -R gruppo percorso/a/directory
```

- Cambia il gruppo proprietario di un link simbolico:

```bash
chgrp -h gruppo path/to/symlink
```

- Cambia il gruppo proprietario di un file/directory rendendolo uguale a quello di un altro file di riferimento:

```bash
chgrp --reference=percorso/al/file_riferimento percorso/al/file
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chgrp: add more information link (#5554) | 2021-03-30T12:33:21 | [1bee28dd6572](https://github.com/tldr-pages/tldr/commit/1bee28dd6572c855d7cdb2ffd88e05794a8cfc86)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | chgrp: add Italian translation. | 2019-03-03T23:44:18 | [90a7a2024d15](https://github.com/tldr-pages/tldr/commit/90a7a2024d150f9f133cfa32cd86f2e062d2765a)

