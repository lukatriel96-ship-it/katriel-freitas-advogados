# Páginas de áreas jurídicas — Katriel & Freitas Advogados

Este pacote foi preparado para ser incorporado à raiz do repositório atual.

## Arquivos incluídos

- `areas.css`: estilos compartilhados pelas páginas internas.
- `beneficios-assistenciais-previdenciarios/index.html`
- `direito-criminal/index.html`
- `direito-empresarial/index.html`
- `direito-civil-consumidor/index.html`
- `direito-administrativo-tributario/index.html`
- `sitemap.xml`: versão atualizada com as novas URLs.
- `links-para-index.html`: links que devem substituir ou complementar os links internos da página inicial.

## Publicação

1. Copie as cinco pastas e o arquivo `areas.css` para a raiz do repositório.
2. Substitua o `sitemap.xml` atual pela versão deste pacote.
3. Altere os links da página inicial usando `links-para-index.html` como referência.
4. Inclua “Direito Criminal” entre as opções do campo “Assunto principal” no formulário da página inicial.
5. Faça commit e push. A Vercel deverá realizar novo deploy automaticamente, caso a integração com o repositório esteja ativa.

## Revisões necessárias antes da publicação

- Confirme que todos os serviços descritos correspondem à atuação efetivamente oferecida pelo escritório.
- Revise especialmente a página de Direito Criminal, pois essa área ainda não aparece na página inicial atual.
- Confirme o número de WhatsApp utilizado nos botões (`55 21 96539-8090`).
- Verifique a redação institucional segundo as normas éticas e disciplinares aplicáveis à publicidade jurídica.

## Observação técnica

As páginas usam `../styles.css`, `../script.js` e `../assets/favicon.svg`, já existentes no repositório. Não há dependência de framework, banco de dados ou etapa de build.
