---
title: 'Two Forms of Pre-rendering'
date: '2020-01-01'
---

Next.js has two forms of pre-rendering: **Static Generation** and **Server-side Rendering**. The difference is in **when** it generates the HTML for a page.

- **Static Generation** is the pre-rendering method that generates the HTML at **build time**. The pre-rendered HTML is then _reused_ on each request.
- **Server-side Rendering** is the pre-rendering method that generates the HTML on **each request**.

Importantly, Next.js lets you **choose** which pre-rendering form to use for each page. You can create a "hybrid" Next.js app by using Static Generation for most pages and using Server-side Rendering for others.

**Tradução** 

Next.js tem duas formas de pré-renderização: **Geração estática** e **Renderização do lado do servidor**. A diferença está em **quando** gera o HTML para uma página.

- **Geração estática** é o método de pré-renderização que gera o HTML no **tempo de compilação**. O HTML pré-renderizado é então _reutilizado_ em cada solicitação.
- **Renderização do lado do servidor** é o método de pré-renderização que gera o HTML em **cada solicitação**.

É importante ressaltar que Next.js permite que você **escolha** qual formulário de pré-renderização usar para cada página. Você pode criar um aplicativo Next.js "híbrido" usando a geração estática para a maioria das páginas e a renderização do lado do servidor para outras.
