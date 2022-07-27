---
author: ['San Baby Francis']
date: 1634263773
title: "snap, TLDR Pages"
description: "snap, സ്നാപ്പ് സെൽഫ് കൺറ്റൈൻഡ് പാക്കേജുകൾ നിയന്ത്രിക്കുവാനുള്ള യൂട്ടിലിറ്റി."
categories: "linux"
---
> `apt` നോട് സാദൃശ്യമുള്ളത്.

- ഒരു പാക്കേജ് സെർച്ച് ചെയ്യുവാൻ:

```bash
snap find പാക്കേജിന്റെ_പേര്
```

- ഒരു പാക്കേജ് ഇൻസ്റ്റാൾ ചെയ്യുവാൻ:

```bash
snap install പാക്കേജിന്റെ_പേര്
```

- ഒരു പാക്കേജ് അപ്ഡേറ്റ് ചെയ്യുവാൻ:

```bash
snap refresh പാക്കേജിന്റെ_പേര്
```

- ഒരു പാക്കേജ് മറ്റൊരു ചാനലിലേക്ക് അപ്ഡേറ്റ് ചെയ്യുവാൻ (ട്രാക്ക്, റിസ്ക്, ബ്രാഞ്ച്):

```bash
snap refresh പാക്കേജിന്റെ_പേര് --channel=ചാനൽ
```

- എല്ലാ പാക്കേജുകളും അപ്ഡേറ്റ് ചെയ്യുവാൻ:

```bash
snap refresh
```

- ഇൻസ്റ്റാൾ ചെയ്യപ്പെട്ട സോഫ്ട്‍വെയറുകൾ കാണുവാൻ:

```bash
snap list
```

- ഒരു പാക്കേജ് അൺഇൻസ്റ്റാൾ ചെയ്യുവാൻ:

```bash
snap remove പാക്കേജിന്റെ_പേര്
```

- സിസ്റ്റത്തിലെ സ്നാപ്പ് ചേഞ്ചുകൾ അറിയുവാൻ:

```bash
snap changes
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[San Baby Francis](mailto:san.baby.francis123@gmail.com) | snap: add Malayalam translation (#6967) | 2021-10-15T04:09:33 | [5f5826f8e9a0](https://github.com/tldr-pages/tldr/commit/5f5826f8e9a062accd46f22940c3d461170454ae)

