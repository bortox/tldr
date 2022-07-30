---
author: ['Alex']
date: 1585564798
title: "binwalk"
description: "binwalk, Firmware Analysis Tool."
categories: "linux"
---
> More information: <https://github.com/ReFirmLabs/binwalk>.

- Scan a binary file:

```bash
binwalk path/to/binary
```

- Extract files from a binary, specifying the output directory:

```bash
binwalk --extract --directory output_directory path/to/binary
```

- Recursively extract files from a binary limiting the recursion depth to 2:

```bash
binwalk --extract --matryoshka --depth 2 path/to/binary
```

- Extract files from a binary with the specified file signature:

```bash
binwalk --dd 'png image:png' path/to/binary
```

- Analyze the entropy of a binary, saving the plot with the same name as the binary and `.png` extension appended:

```bash
binwalk --entropy --save path/to/binary
```

- Combine entropy, signature and opcodes analysis in a single command:

```bash
binwalk --entropy --signature --opcodes path/to/binary
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex](mailto:alexandre.dhondt@gmail.com) | binwalk: add page (#3943) | 2020-03-30T12:39:58 | [0cace23c9c23](https://github.com/tldr-pages/tldr/commit/0cace23c9c23eeae4cb4fdb3697d0aee45a0e386)

