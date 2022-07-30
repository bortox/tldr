---
author: ['Andrik Albuquerque', 'Lucas Gabriel Schneider']
date: 1612112718
title: "cpdf"
description: "cpdf, CLI to manipulate existing PDF files in a variety of ways."
categories: "common"
---
> More information: <https://www.coherentpdf.com/cpdfmanual/cpdfmanual.html>.

- Select pages 1, 2, 3 and 6 from a source document and write those to a destination document:

```bash
cpdf path/to/source_document.pdf 1-3,6 -o path/to/destination_document.pdf
```

- Merge two documents into a new one:

```bash
cpdf -merge path/to/source_document_one.pdf path/to/source_document_two.pdf -o path/to/destination_document.pdf
```

- Show the bookmarks of a document:

```bash
cpdf -list-bookmarks path/to/document.pdf
```

- Split a document into ten-page chunks, writing them to `chunk001.pdf`, `chunk002.pdf`, etc:

```bash
cpdf -split path/to/document.pdf -o path/to/chunk%%%.pdf -chunk 10
```

- Encrypt a document using 128bit encryption, providing `fred` as owner password and `joe` as user password:

```bash
cpdf -encrypt 128bit fred joe path/to/source_document.pdf -o path/to/encrypted_document.pdf
```

- Decrypt a document using the owner password `fred`:

```bash
cpdf -decrypt path/to/encrypted_document.pdf owner=fred -o path/to/decrypted_document.pdf
```

- Show the annotations of a document:

```bash
cpdf -list-annotations path/to/document.pdf
```

- Create a new document from an existing one with additional metadata:

```bash
cpdf -set-metadata path/to/metadata.xml path/to/source_document.pdf -o path/to/destination_document.pdf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Andrik Albuquerque](mailto:andrik.albuquerque@gmail.com) | cpdf: applying tokens and fix more information label (#3720) | 2020-01-01T03:14:03 | [82ae3bc0db78](https://github.com/tldr-pages/tldr/commit/82ae3bc0db78aba000fde07426a5349b90869897)
[Andrik Albuquerque](mailto:andrik.albuquerque@gmail.com) | cpdf: add page (#3713) | 2019-12-31T02:18:28 | [db65c5bfb41e](https://github.com/tldr-pages/tldr/commit/db65c5bfb41e1ebf919f8d29286ddf20f546f513)

