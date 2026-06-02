# Wiki Standards

Repositório de consulta de normas contábeis, com navegação por famílias, catálogos e páginas de equivalência entre pronunciamentos relacionados.

Aqui você encontra os textos normativos preservados e páginas auxiliares para localizar normas por código, tema e relação com outros pronunciamentos.

## Project Structure

```text
wikistandards/
├── README.md                         # Visão geral do repositório
├── home.md                           # Página inicial do site
├── _sidebar.md                       # Navegação principal
├── index.html                        # Casca de publicação do Docsify
├── catalogo/                         # Índices, mapas e equivalências
├── families/                         # Páginas por família normativa
├── normas/                           # Textos normativos preservados
├── assets/                           # Identidade visual e recursos estáticos
├── PROMPT-EDITORIAL-SESSAO.md        # Prompt base para sessões editoriais
├── LISTA-MESTRA-ESCOPO-EDITORIAL.md  # Controle mestre do escopo editorial
├── CONTROLE-EDITORIAL.md             # Acompanhamento editorial auxiliar
├── BACKLOG.md                        # Pendências e melhorias mapeadas
├── NOTICE.md                         # Avisos sobre conteúdo de terceiros
└── LICENSE                           # Licença da infraestrutura do projeto
```

## Como usar

- Use `catalogo/` para localizar normas por família, código e título.
- Use a página de equivalências para consultar relações entre CPC, NBC TG e IFRS.
- Use `normas/` quando quiser abrir diretamente o texto da norma.

## Política de Conteúdo

Os textos em `normas/` devem ser preservados. A organização, os índices e a contextualização ficam nas páginas de catálogo e equivalências.

## Licenciamento

O repositório usa licença MIT para a infraestrutura original do projeto, incluindo código, scripts, estrutura do site, navegação e materiais autorais próprios.

Os textos normativos e outros materiais de terceiros presentes em `normas/` não passam a ser MIT por estarem aqui. Eles continuam sujeitos aos direitos autorais e aos termos de uso de seus respectivos titulares, incluindo IFRS Foundation e FACPCS/CPC, quando aplicável.

Leia [`NOTICE.md`](NOTICE.md) antes de redistribuir, espelhar ou reutilizar o conteúdo normativo deste repositório.
