---
author: ['Lucas Gabriel Schneider', 'Schneider', 'Mikhail Katychev']
date: 1582218028
title: "sops, TLDR Pages"
description: "sops, SOPS: Secrets OPerationS."
categories: "common"
---
> Tool for managing secrets.

> More information: <https://github.com/mozilla/sops>.

- Encrypt a file:

```bash
sops -e path/to/myfile.json > path/to/myfile.enc.json
```

- Decrypt a file to the standard output:

```bash
sops -d path/to/myfile.enc.json
```

- Rotate data keys for a sops file:

```bash
sops -r path/to/myfile.enc.yaml
```

- Change the extension of the file once encrypted:

```bash
sops -d --input-type json path/to/myfile.enc.json
```

- Extract keys by naming them, and array elements by numbering them:

```bash
sops -d --extract '["an_array"][1]' path/to/myfile.enc.json
```

- Show the difference between two sops files:

```bash
diff <(sops -d path/to/secret1.enc.yaml) <(sops -d path/to/secret2.enc.yaml)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | sops: rephrase description Co-Authored-By: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-02-20T18:00:28 | [4e0d7702df60](https://github.com/tldr-pages/tldr/commit/4e0d7702df6084ddbf7a3e03758d13f7f4ff4338)
[Schneider](mailto:lucas.schneider@sap.com) | sops: remove adjectives | 2020-02-20T18:00:28 | [5682556a79db](https://github.com/tldr-pages/tldr/commit/5682556a79db86bfe8a24e2aa2944e12f4ee9957)
[Mikhail Katychev](mailto:mkatych@gmail.com) | sops: add page (#3667) * sops: add page * added period * modified file example * to infinitive and beyond * Update [...] | 2019-12-24T18:04:03 | [4de3a27bfa92](https://github.com/tldr-pages/tldr/commit/4de3a27bfa922010d17c166609271e5b39c849de)

