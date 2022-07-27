---
author: ['Diego B. Fernandez', 'bl-ue']
date: 1610731489
title: "clj, TLDR Pages"
description: "clj, Ferramenta de Clojure para iniciar um REPL ou invocar uma função com argumentos."
categories: "common"
---
> Todas as opções podem ser definidas em um arquivo `deps.edn`.

> Mais informações: <https://clojure.org/guides/deps_and_cli>.

- Inicia um REPL:

```bash
clj
```

- Executa uma função:

```bash
clj -X namespace/function_name
```

- Executa a função principal (*main*) do *namespace* especificado:

```bash
clj -M -m namespace args
```

- Prepara um projeto resolvendo dependências, baixando bibliotecas, e criando / cacheando *classpaths*:

```bash
clj -P
```

- Inicia um servidor nREPL com o *middleware* CIDER:

```bash
clj -Sdeps '{:deps {nrepl {:mvn/version "0.7.0"} cider/cider-nrepl {:mvn/version "0.25.2"}' -m nrepl.cmdline --middleware '["cider.nrepl/cider-middleware"]' --interactive
```

- Inicia um REPL para ClojureScript e abre um navegador web:

```bash
clj -Sdeps '{:deps {org.clojure/clojurescript {:mvn/version "1.10.758"}' --main cljs.main --repl
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Diego B. Fernandez](mailto:diegobfernandez@outlook.com) | clj: add pt_BR translation (#5051) | 2020-12-30T14:31:51 | [493632b02b20](https://github.com/tldr-pages/tldr/commit/493632b02b2047bb0923903211f1b4a2f2fcedec)

