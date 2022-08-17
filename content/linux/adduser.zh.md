---
author: ['Patrice Denis', 'Ein Verne', 'bl-ue', 'hugue', 'Seth Falco', 'marchersimon', '千玄子']
date: 1660628187
title: "adduser"
description: "adduser, 添加用户的工具。"
categories: "linux"
---
> 更多信息：<https://manpages.debian.org/latest/adduser/adduser.html>.

- 创建一个新用户，在默认路径创建 home 目录，并提示用户设置密码：

```bash
adduser 用户名
```

- 创建一个新用户，不生成 home 目录：

```bash
adduser --no-create-home 用户名
```

- 创建一个新用户，并在指定路径下创建 home 目录：

```bash
adduser --home home 路径 用户名
```

- 创建一个新用户，并指定登录 shell：

```bash
adduser --shell shell 路径 用户名
```

- 创建一个新用户，并指定其用户组：

```bash
adduser --ingroup 用户组 用户名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | adduser: update Chinese translation (#8356) | 2022-08-16T07:36:27 | [e045c22ad6b1](https://github.com/tldr-pages/tldr/commit/e045c22ad6b1e7e377cd89a8b2c11e189abdda7a)
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[千玄子](mailto:ownbyzjuyk@gmail.com) | adduser, apt-*, apt, aptitude, at: update Chinese translation (#6400) | 2021-08-23T21:25:59 | [ff74227350e9](https://github.com/tldr-pages/tldr/commit/ff74227350e9b89a9501ddbf39089ed60876201c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Patrice Denis](mailto:patrice.denis@gmail.com) | user*, group*, add*, group*: add more info links (#5738) * user*, group*, add*, group*:add more info links * user*, group*: remove [...] | 2021-04-17T14:19:41 | [ce747d2f46f4](https://github.com/tldr-pages/tldr/commit/ce747d2f46f40836209afcd06898073ddabbc520)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[hugue](mailto:hugue_liu@yahoo.com) | move Chinese pages from pages.cn to pages.zh Also add new Chinese translations for apt, aptitude and arch. | 2019-01-09T05:33:44 | [11f109b466cf](https://github.com/tldr-pages/tldr/commit/11f109b466cf35daefdde57a1ca2e0261f90555c)

