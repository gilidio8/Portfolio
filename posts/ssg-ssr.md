---
title: 'When to Use Static Generation v.s. Server-side Rendering'
date: '2020-01-02'
---

We recommend using **Static Generation** (with and without data) whenever possible because your page can be built once and served by CDN, which makes it much faster than having a server render the page on every request.

You can use Static Generation for many types of pages, including:

- Marketing pages
- Blog posts
- E-commerce product listings
- Help and documentation

You should ask yourself: "Can I pre-render this page **ahead** of a user's request?" If the answer is yes, then you should choose Static Generation.

On the other hand, Static Generation is **not** a good idea if you cannot pre-render a page ahead of a user's request. Maybe your page shows frequently updated data, and the page content changes on every request.

In that case, you can use **Server-Side Rendering**. It will be slower, but the pre-rendered page will always be up-to-date. Or you can skip pre-rendering and use client-side JavaScript to populate data.

**Tradução**

Recomendamos o uso de **Geração estática** (com e sem dados) sempre que possível porque sua página pode ser construída uma vez e servida por CDN, o que torna muito mais rápido do que ter um servidor renderizando a página em cada solicitação.

Você pode usar a Geração estática para muitos tipos de páginas, incluindo:

- Páginas de marketing
- Postagens no blog
- Listagens de produtos de comércio eletrônico
- Ajuda e documentação

Você deve se perguntar: "Posso pré-renderizar esta página **antes** da solicitação de um usuário?" Se a resposta for sim, você deve escolher Geração estática.

Por outro lado, a Geração estática **não** é uma boa ideia se você não pode pré-renderizar uma página antes da solicitação do usuário. Talvez sua página mostre dados atualizados com frequência e o conteúdo da página mude a cada solicitação.

Nesse caso, você pode usar **Renderização do lado do servidor**. Será mais lento, mas a página pré-renderizada estará sempre atualizada. Ou você pode pular a pré-renderização e usar JavaScript do lado do cliente para preencher os dados.

