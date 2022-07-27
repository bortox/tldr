---
author: ['Jonathan Reyes']
date: 1643817049
title: "dig, TLDR Pages"
description: "dig, Utilidad de consulta para DNS."
categories: "common"
---
> Más información: <https://manned.org/dig>.

- Consulta la(s) IP(s) asociadas a un nombre de equipo (registros A):

```bash
dig +short example.com
```

- Obtiene una respuesta detallada para un dominio determinado (registros A):

```bash
dig +noall +answer example.com
```

- Consulta un tipo de registro DNS específico asociado a un dominio determinado:

```bash
dig +short example.com A|MX|TXT|CNAME|NS
```

- Obtiene todos los tipos de registros para un dominio determinado:

```bash
dig example.com ANY
```

- Especifíca un servidor DNS alterno a consultar:

```bash
dig @8.8.8.8 example.com
```

- Realiza una búsqueda DNS inversa para una dirección IP (registro PTR):

```bash
dig -x 8.8.8.8
```

- Encuentra servidores de nombre autoritativos para la zona y muestra registros SOA:

```bash
dig +nssearch example.com
```

- Realiza consultas iterativas y muestra el trazado de ruta completo para resolver un dominio:

```bash
dig +trace example.com
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[Jonathan Reyes](mailto:jreyes33@users.noreply.github.com) | df, dig, du, ln, tree: add Spanish translation (#7726) | 2022-02-02T16:50:49 | [256e1c28c4d2](https://github.com/tldr-pages/tldr/commit/256e1c28c4d2924592afb10eafce03fb27612809)

