---
author: ['Reinhart Previano Koentjoro']
date: 1657669284
title: "Invoke-WebRequest, TLDR Pages"
description: "Invoke-WebRequest, Performs a HTTP/HTTPS request to the Web."
categories: "windows"
---
> This command can only be used through PowerShell.

> More information: <https://docs.microsoft.com/powershell/module/microsoft.powershell.utility/invoke-webrequest>.

- Download the contents of a URL to a file:

```bash
Invoke-WebRequest http://example.com -OutFile filename
```

- Send form-encoded data (POST request of type `application/x-www-form-urlencoded`):

```bash
Invoke-WebRequest -Method Post -Body @{ name='bob' } http://example.com/form
```

- Send a request with an extra header, using a custom HTTP method:

```bash
Invoke-WebRequest -Headers @{ X-My-Header = '123' } -Method PUT http://example.com
```

- Send data in JSON format, specifying the appropriate content-type header:

```bash
Invoke-WebRequest -Body '{"name":"bob"}'  -ContentType 'application/json' http://example.com/users/1234
```

- Pass a username and password for server authentication:

```bash
Invoke-WebRequest -Headers @{ Authorization = "Basic "+ [System.Convert]::ToBase64String([System.Text.Encoding]::ASCII.GetBytes("myusername:mypassword")) } http://example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | invoke-webrequest: add page (#8177) * windows/get-*: Add PowerShell-only notice * Update pages/windows/get-childitem.md Co-authored- [...] | 2022-07-13T01:41:24 | [dc3ec3556046](https://github.com/tldr-pages/tldr/commit/dc3ec3556046aa804d0224bb54dd27ab6001e449)

