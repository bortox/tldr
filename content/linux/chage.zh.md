---
author: ['Axel Navarro', 'anderly011']
date: 1632142761
title: "chage"
description: "chage, 更改用户账户和密码到期信息。"
categories: "linux"
---
> 更多信息：<https://manned.org/chage>.

- 列出用户的密码信息：

```bash
chage --list 用户名
```

- 启用密码在 10 天内过期：

```bash
sudo chage --maxdays 10 用户名
```

- 关闭密码过期：

```bash
sudo chage --maxdays -1 用户名
```

- 设置账户到期日期：

```bash
sudo chage --expiredate YYYY-MM-DD 用户名
```

- 强制用户在下次登录时更改密码：

```bash
sudo chage --lastday 0 用户名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | chage: fix examples and use long arguments (#6541) | 2021-09-20T14:59:21 | [61da0633dea9](https://github.com/tldr-pages/tldr/commit/61da0633dea9e2d5f0235a82d86351bf1d11e664)
[anderly011](mailto:90740476+anderly011@users.noreply.github.com) | cal, chage: add Chinese translation (#6529) | 2021-09-15T14:14:54 | [6e19670c2fe4](https://github.com/tldr-pages/tldr/commit/6e19670c2fe4f5c254b0cc6241faf567f8412449)

