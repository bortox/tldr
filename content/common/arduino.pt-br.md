---
author: ['Luis Felipe Santos do Nascimento']
date: 1620319123
title: "arduino, TLDR Pages"
description: "arduino, Arduino Studio - Ambiente de Desenvolvimento Integrado para a plataforma Arduino."
categories: "common"
---
> Mais informações: <https://github.com/arduino/Arduino/blob/master/build/shared/manpage.adoc>.

- Compilar um sketch:

```bash
arduino --verify caminho/para/arquivo.ino
```

- Compilar e enviar sketch:

```bash
arduino --upload caminho/para/arquivo.ino
```

- Compilar e enviar sketch para um Arduino Nano com uma CPU Atmega328p, conectada na porta `/dev/ttyACM0`:

```bash
arduino --board arduino:avr:nano:cpu=atmega328p --port /dev/ttyACM0 --upload caminho/para/arquivo.ino
```

- Definir a preferência `nome` para um determinado `valor`:

```bash
arduino --pref nome=valor
```

- Compilar um sketch, colocar o resultado da compilação no diretório de compilação, e reutilizar qualquer resultado pre-existente neste diretório:

```bash
arduino --pref build.path=caminho/para/diretório --verify caminho/para/arquivo.ino
```

- Salvar todas as preferências (alteradas) para `preferences.txt`:

```bash
arduino --save-prefs
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Luis Felipe Santos do Nascimento](mailto:luisfelipesdn12@gmail.com) | [, arduino-builder, arduino, bash, clear: add pt-BR translation (#5874) | 2021-05-06T18:38:43 | [0a5e31e1c7f3](https://github.com/tldr-pages/tldr/commit/0a5e31e1c7f3a48ec206ca07bb1ffb1cd0fb39c0)

