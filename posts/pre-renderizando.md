---
title: 'Duas formas de Pré-renderizar'
date: '2021-08-17'
---

O Next.js possui duas formas de pré-renderização: **Geração Estática** e **Renderização server-side**. A diferença está em **quando** ele gera o HTML para uma página.

- **Geração Estática** é o método de pré-renderização que gera o HTML no **tempo de construção**. O HTML pré-renderizado é então_reusado_ em cada requisição.
- **Renderização Server-Side** é o método de pré-renderização que gera o HTML em **cada requisição**.

É importante ressaltar que o Next.js deixa você **escolher** qual forma de pré-renderização usar em cada página. Você pode criar um aplicativo Next.js "híbrido" usando a Geração Estática para a maioria das páginas e usando Renderozação Server-Side para as outras.