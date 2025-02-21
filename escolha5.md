# 5. Escolha de Framework para Frontend: Next.js

## Status

Aceita

## Contexto

Precisamos de um framework frontend que suporte renderização no lado do servidor (SSR), fácil integração com APIs e suporte para criar um frontend dinâmico e otimizado.

## Decisão

Escolhemos o **Next.js** devido ao seu suporte nativo para SSR (Server-Side Rendering) e SSG (Static Site Generation), além de sua integração direta com React e facilidade para integrar com APIs do backend, como o FastAPI.

## Consequências

- **Positivas**:
  - SSR melhora o SEO e a performance do frontend.
  - Suporte para funcionalidades como roteamento dinâmico e otimização de imagens.
  - Integração fácil com o backend, permitindo a criação de aplicações full-stack.
  
- **Negativas**:
  - Embora Next.js facilite muito o desenvolvimento, pode ser mais complexo para iniciantes comparado a soluções mais simples.
  - Algumas funcionalidades de SSR podem introduzir complexidade adicional dependendo do caso de uso.

## Alternativas Consideradas

- **React**: React puro também seria uma opção, mas não ofereceria as funcionalidades nativas de SSR e otimização que o Next.js oferece.