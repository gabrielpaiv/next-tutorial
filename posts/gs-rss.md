---
title: 'Quando usar Geração Estática vs Renderização Server-Side'
date: '2021-08-16'
---

Nós recomendamos usar **Geração Estática** (com ou sem dados) sempre que possivel, porque sua página pode ser construída uma vez e servida por CDN, o que faz ele muito mais rápido do que tendo uma página renderizada pelo servidor em cada requisição.

Você pode usar Geração Estática para vários tipos de página, incluindo:

- Páginas de Marketing
- Postagens em blog
- Listagem de produtos de E-commerce
- Ajuda e documentação

Você precisa se perguntar: "Eu posso pré-renderizar esta página **antes** da requisição de um usuário?" Se a resposta for sim, então você deve escolher a Geração Estática.

Por outro lado, a Geração Estática **não** é uma boa ideia se você não pode pré-renderizar uma página antes da requisição do usuário. Talvez sua página mostra conteúdos frequentemente atualizados, e o conteúdo da página muda em cada requisição.

Nesse caso, você pode usar **Renderização Server-Side**. Será mais lento, mas a página pré-renderizada sempre estará atualizada. Ou você pode pular a pré-renderização e usar Javascript do client-side para popular dados.