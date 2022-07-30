---
author: ['千玄子', 'Stig124', 'bl-ue', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "authconfig"
description: "authconfig, 用于设置系统认证资源的命令行界面。"
categories: "linux"
---
> 更多信息：<https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/system-level_authentication_guide/authconfig-install>.

- 显示当前的配置（或空运行）：

```bash
authconfig --test
```

- 设置服务器使用另一种不同的密码散列算法：

```bash
authconfig --update --passalgo=算法名
```

- 启用 LDAP 认证：

```bash
authconfig --update --enableldapauth
```

- 关闭 LDAP 认证：

```bash
authconfig --update --disableldapauth
```

- 开启网络信息服务（NIS）：

```bash
authconfig --update --enablenis
```

- 开启 Kerberos：

```bash
authconfig --update --enablekrb5
```

- 开启 Winbind（活动目录）认证：

```bash
authconfig --update --enablewinbindauth
```

- 开启本地认证：

```bash
authconfig --update --enablelocauthorize
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[千玄子](mailto:ownbyzjuyk@gmail.com) | a2dismod to avahi-browse: add Chinese translation (#5246) | 2021-05-01T20:43:23 | [92f09753c6de](https://github.com/tldr-pages/tldr/commit/92f09753c6de9ab7cc8df9cd8d194f824252dd23)

