# Pontual Sinal de Celulares — redesign

Site estático, responsivo e sem dependências externas. Pode ser publicado em hospedagem comum, Cloudflare Pages, Netlify, Vercel ou GitHub Pages.

## Arquivos principais

- `index.html`: página inicial
- `repetidor-de-sinal-celular.html`: landing page SEO do serviço principal
- `solucoes-para-empresas.html`: página comercial B2B
- `visita-tecnica.html`: página sobre diagnóstico técnico
- `sobre.html`: institucional
- `contato.html`: formulário que abre a solicitação pronta no WhatsApp
- `robots.txt` e `sitemap.xml`: rastreamento e indexação
- `assets/css/styles.css`: identidade visual e responsividade
- `assets/js/main.js`: menu, animações leves e formulário

## Publicação

1. Faça backup do site antigo.
2. Envie todo o conteúdo desta pasta para a raiz pública do domínio.
3. Mantenha o domínio canônico como `https://www.pontualtele.com/` ou ajuste todas as tags `canonical`, o sitemap e o robots.txt caso prefira a versão sem `www`.
4. Configure redirecionamento 301 da versão não canônica para a canônica.
5. Cadastre e valide o domínio no Google Search Console.
6. Envie `https://www.pontualtele.com/sitemap.xml` no Search Console.
7. Teste os dados estruturados no Rich Results Test e as páginas no PageSpeed Insights.

## Pontos que merecem confirmação antes de publicar

- área exata de atendimento;
- horário comercial;
- endereço que pode ser exibido publicamente;
- CNPJ e razão social no rodapé, caso desejado;
- logotipo definitivo, caso exista um arquivo oficial em alta resolução.

## SEO implementado

- títulos e descrições exclusivos;
- URLs focadas por intenção de busca;
- canonical;
- Open Graph e Twitter Cards;
- JSON-LD de LocalBusiness, Organization, Service e BreadcrumbList;
- sitemap XML;
- robots.txt;
- HTML semântico e hierarquia correta de títulos;
- conteúdo local e termos de serviço usados naturalmente;
- carregamento leve, sem bibliotecas externas;
- acessibilidade, foco visível e suporte a redução de movimento.
