---
author: ['程亦超(何兮)', 'Waldir Pimenta', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1623219131
title: "odps auth"
description: "odps auth, User authorities in ODPS (Open Data Processing Service)."
categories: "common"
---
> See also `odps`.

> More information: <https://www.alibabacloud.com/help/doc-detail/27971.htm>.

- Add a user to the current project:

```bash
add user username;
```

- Grant a set of authorities to a user:

```bash
grant action_list on object_type object_name to user username;
```

- Show authorities of a user:

```bash
show grants for username;
```

- Create a user role:

```bash
create role role_name;
```

- Grant a set of authorities to a role:

```bash
grant action_list on object_type object_name to role role_name;
```

- Describe authorities of a role:

```bash
desc role role_name;
```

- Grant a role to a user:

```bash
grant role_name to username;
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | opds*: add link and see also note (#6074) | 2021-06-09T08:12:11 | [b139da2bb6f8](https://github.com/tldr-pages/tldr/commit/b139da2bb6f8c8cb24c1948278fdd6247ec7ffd3)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: change user_name to username (#3841) | 2020-02-08T19:56:05 | [26e019b295f1](https://github.com/tldr-pages/tldr/commit/26e019b295f1782e6dd695b03108f061946327e8)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-auth: reorder commands Change-Id: I58c9b5451853171cd5d084877576f606068d1984 | 2016-05-16T09:17:01 | [b75e25a7fb6e](https://github.com/tldr-pages/tldr/commit/b75e25a7fb6ef0e70e0ebed63583703fb88a6811)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-auth: add desc role Change-Id: I76664ed2070a2367071e25a1640dbf0055721ae6 | 2016-05-16T03:43:04 | [e9fe30d3293f](https://github.com/tldr-pages/tldr/commit/e9fe30d3293f1446f79e1a879b0ce05e01f12150)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | odps-auth: phrase second example to match others | 2016-05-15T12:45:33 | [3d8326e4dd57](https://github.com/tldr-pages/tldr/commit/3d8326e4dd570e13f8e9861ade79a6baaf70fc04)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-auth: {{object}} to {{object_type}} Change-Id: Icbbd48ce29c3687cebae78dd1c965d85aae7aae1 | 2016-05-15T04:56:50 | [443a206d19c8](https://github.com/tldr-pages/tldr/commit/443a206d19c8805eab2bc461a923b3b17410ae69)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-auth: update Change-Id: Ibdf4b76b3c720610d1abf48dd29e173c02cd51f4 | 2016-05-14T05:20:48 | [e3e486e0802d](https://github.com/tldr-pages/tldr/commit/e3e486e0802d3a29c2882376649b3316f457e654)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-auth: typo Change-Id: I2a8ea11be6267868c790eb6357c525c6b1d79715 | 2016-05-12T15:20:57 | [df4710948162](https://github.com/tldr-pages/tldr/commit/df4710948162b15e4cb921617e78cdbdc06cadb7)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-auth: update Change-Id: I7164568e8ee03ae503cf07cf6bbd5d370395e428 | 2016-05-12T15:19:55 | [18d901ba4662](https://github.com/tldr-pages/tldr/commit/18d901ba4662c774c40bc5817ff9cc39dc06a371)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-auth: shorthand Change-Id: I3a0cd20a86c78b2a596e1c2175149ebe93f1d5e1 | 2016-05-12T15:08:15 | [995fa026310e](https://github.com/tldr-pages/tldr/commit/995fa026310e90d93534c875cbbc4f4f673f3783)
[程亦超(何兮)](mailto:yichao.cheng@alibaba-inc.com) | odps-auth: add page Change-Id: Ic871dd39c9b866054fde3f7c083b145d4c7e9a72 | 2016-05-12T15:05:53 | [b67da53549b5](https://github.com/tldr-pages/tldr/commit/b67da53549b5484554a14153bb05a34d5a4179e8)

