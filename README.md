# Glossário do NextJS

- **Static**
  - Por padrão
  - Só vai usar o `next export`, em casos onde TUDO é pré-renderizado
  - `getStaticProps`: versão com menos recursos

- **SSG(Static Site Generation)**:
  - `getStaticProps`
    - `revalidate`: true [npm run build && npm start]
  - **Incremental Static Generation** [npm run build && npm start]
    - fallback: true || 'blocking' e o getStaticPaths vem vazio ou com somente alguns itens


- **SSR(Server Side Render)**:
  - `getServerSideProps`
  - Se tiver dentro da pasta `/api` é uma API Route e é SSR



- **Canal**
  - DEV Soutinho

- **Ferramentas**
  - Calibre
  - Sentry - Monitoração de Erro
  - Vercel é uma ferramenta de hospedagem simples
  - AWS SImplify
  - Heroku
  - DigitalOcean
  - Netlify
