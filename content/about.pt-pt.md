---
date: 2021-11-17
title: "Sobre as Páginas TLDR"
description: "O que são Páginas TLDR? Como contribuir? O que é este website?"
---

> Atenção: esta página é automaticamente traduzida - ao contrário das Páginas TLDR neste website - por isso pode haver erros de tradução

![TLDR Pages Logo](/tldr-logo.png)

|Gitter|PRs|Contributors|Build Status|LICENSE|
|---|---|---|---|---|
[![Gitter chat][gitter-image]][gitter-url]|[![Merged PRs][prs-merged-image]][prs-merged-url]|[![GitHub contributors][contributors-image]][contributors-url]|[![Build status][github-actions-image]][github-actions-url]|[![license][license-image]][license-url]

[github-actions-url]: https://github.com/tldr-pages/tldr/actions
[github-actions-image]: https://img.shields.io/github/workflow/status/tldr-pages/tldr/CI.svg
[gitter-url]: https://gitter.im/tldr-pages/tldr
[gitter-image]: https://img.shields.io/badge/chat-on_gitter-deeppink
[prs-merged-url]: https://github.com/tldr-pages/tldr/pulls?q=is:pr+is:merged
[prs-merged-image]: https://img.shields.io/github/issues-pr-closed-raw/tldr-pages/tldr.svg?label=merged+PRs&color=green
[contributors-url]: https://github.com/tldr-pages/tldr/graphs/contributors
[contributors-image]: https://img.shields.io/github/contributors-anon/tldr-pages/tldr.svg
[license-url]: https://github.com/tldr-pages/tldr/blob/main/LICENSE.md
[license-image]: https://img.shields.io/badge/license-CC_BY_4.0-blue.svg
</div>

## O que são as páginas tldr?

O projecto **tldr-páginas*** é uma colecção de páginas de ajuda mantidas em colaboração
para ferramentas de linha de comando que fornecem um complemento mais simples e mais acessível aos instrumentos tradicionais
às [páginas de homem] tradicionais (https://en.wikipedia.org/wiki/Man_page).

Talvez seja novo no mundo das linhas de comando? Talvez esteja um pouco enferrujado ou nem sempre se lembre dos argumentos para comandos como "isof" ou "tar"?

Não ajuda certamente que a primeira opção explicada em `man tar` seja:

```
-b bloco
   Especificar o tamanho do bloco, em registos de 512 bytes, para E/S de unidade de fita adesiva.
   Normalmente, este argumento só é necessário quando se lê ou escreve em unidades de fita adesiva,
   e normalmente nem sequer nessa altura, uma vez que o tamanho padrão do bloco de 20 registos (10240 bytes) é muito comum.
```

Parece haver espaço para páginas de ajuda mais simples que se concentrem em exemplos práticos.
Que tal:

![SVG animado do cliente tldr mostrando o comando tar](/tldr-tar.svg)

> A página TLDR para o comando tar também pode ser encontrada neste sítio [esta ligação](https://tldr.bortox.it/content/common/tar)

Este repositório é precisamente isso: uma colecção de exemplos em constante crescimento.
para as ferramentas de linha de comando mais comuns UNIX, Linux, macOS, SunOS, Android e Windows.

## O que é este site?

O objectivo deste site é fazer das Páginas TLDR, uma colecção de páginas de ajuda geridas pela comunidade
para ferramentas de linha de comando_ para utilizadores da web simplesmente digitando 'TLDR pages + command_name' no seu motor de busca preferido.

Actualmente, não é possível encontrar a página TLDR de um comando com uma simples pesquisa no Google. A situação é ainda pior quando se procura um comando numa língua específica que não seja o inglês, porque há frequentemente sítios web lentos e clickbait.

De facto, este site também apoia comentários e partilha, tornando as páginas TLDR 'amigas da web'. 

### Análise, monitorização e anúncios

É claro que não há **apublicidade***. 

O rastreio é feito com a Matomo. O Matomo está configurado para não recolher ** dados pessoais***[^1], por isso é compatível com GDPR e não requer cookies de banner. Se desejar optar por não participar, [pode fazê-lo aqui](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it).

O site é **hospedado na Europa**, por PHP-Friends. Segundo a web-carbon.com, o centro de dados utiliza **energia sustentável**!

Se quiser **apoiar** o site (pago pelos servidores), pode [**donar algo aqui***](https://bortox.it/contribuisci-cs-en).

### Porquê este site?

1. indexar as páginas TLDR e torná-las facilmente pesquisáveis em linha em múltiplas línguas
2. apenas para escrever algo

### Como é que este site funciona?

* Os ficheiros-fonte TLDR em Markdown e dados Git associados são lidos a partir de um guião (30m).
* As páginas compatíveis com Hugo são criadas pelo guião
* Hugo cria este website (~6500 páginas) em apenas 10 segundos!

### Possíveis novas características

- [ ] Páginas específicas do compromisso
- Tradução automática com DeepL (até 500.000 caracteres/mês na versão gratuita)


## Como usar

Uma forma popular e conveniente de aceder a estas páginas no seu próprio computador
é instalar o [cliente Node.js](https://github.com/tldr-pages/tldr-node-client),
que é apoiado pelos mantenedores do projecto tldr-pages:

``sh
npm instalar -g tldr
```

Em alternativa, pode utilizar o [cliente Python](https://github.com/tldr-pages/tldr-python-client), que pode ser instalado através do `pip3`.

``sh
pip3 instalar tldr
```

Isto dá-lhe acesso directo a um guia simplificado e fácil de ler de comandos como o `tar`,
acessível digitando `tldr tar` em vez do normal `man tar`.

Se quiser uma versão offline sem instalar qualquer software,
ver a [versão PDF](https://tldr.sh/assets/tldr-book.pdf).

Para navegar sem instalar um cliente no seu computador
ver o cliente web em <https://tldr.ostera.io>.

Existem também **vários outros clientes*** fornecidos pela comunidade,
tanto para a linha de comando como para outras plataformas.
Para uma lista completa de clientes, ver a nossa [wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients).


## Como posso contribuir para as páginas tldr?

Todas as contribuições são bem-vindas!

Algumas formas de contribuir são

- Adicionando o seu comando favorito que não está coberto.
- Acrescentar exemplos ou melhorar o conteúdo de uma página existente.
- Acrescentar páginas solicitadas das nossas edições com a etiqueta [ajuda desejada](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22).
- Tradução de páginas em diferentes línguas.

Todas as páginas `tldr` são escritas em Markdown, para que possam ser editadas com bastante facilidade e as alterações possam ser feitas em
com Git na linha de comando ou através do
através da interface web do GitHub.

Esforçamo-nos por manter uma comunidade [acolhedora e colaborativa](https://github.com/tldr-pages/tldr/blob/main/GOVERNANCE.md).
Se é um contribuinte pela primeira vez, dê uma vista de olhos nas [Directrizes de Contribuição](https://github.com/tldr-pages/tldr/blob/main/CONTRIBUTING.md), e comece!

Se desejar contribuir para as traduções, pode <https://lukwebsforge.github.io/tldri18n/>
para ver o progresso geral de todas as traduções e saber quais as traduções que estão em falta ou desactualizadas.

## O que significa 'tldr'?

TL;DR significa "Too long; I have not read" (Tempo demais; não li).
Deriva do jargão da Internet, onde é utilizado para indicar que um texto longo (ou partes dele) foi
(ou partes dele) foi saltado porque é demasiado tempo.
Mais informações em [artigo] por How-To Geek (https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/).

[^1]: Nenhum registo de visitantes, rastreio sem cookies, endereços IP anónimos (2 bytes, como 192.168.xxx.xxx ) de acordo com [guia matomo oficial](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/) ... 