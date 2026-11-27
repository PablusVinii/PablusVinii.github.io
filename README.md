# PablusVinii.github.io

Portfólio técnico e blog pessoal de **Pablus Vinicius** — Especialista em Infraestrutura de TI, Redes, Suporte N3, Automação e Engenharia de Hardware.

## Estrutura

- `index.html` — Página principal (Hero com perfil técnico N3, Frentes de Atuação & Stack, Metodologia RCA em 4 camadas, Trajetória, Blog com busca/filtro e Contato).
- `post.html` — Leitor dinâmico de artigos em Markdown com sanitização (`DOMPurify`), cálculo de tempo de leitura, botão para copiar blocos de código e navegação entre posts.
- `style.css` — Tema dark responsivo, menu mobile, estilos de leitura e acessibilidade.
- `404.html` — Página de erro personalizada para o GitHub Pages.
- `robots.txt` & `sitemap.xml` — Indexação básica para buscadores.
- `posts/index.json` & `posts/*.md` — Índice e artigos publicados manualmente ou automatizados via [autoinsta](https://github.com/PablusVinii/autoinsta).

## Formato de `posts/index.json`

Cada entrada no array JSON segue:

```json
{
  "slug": "exemplo-de-artigo",
  "title": "Título do artigo",
  "excerpt": "Resumo curto exibido no card",
  "category": "Infraestrutura & N3",
  "date": "2026-11-24",
  "readTime": "4 min",
  "file": "posts/exemplo-de-artigo.md",
  "cover": "posts/images/exemplo-de-artigo.png"
}
```
