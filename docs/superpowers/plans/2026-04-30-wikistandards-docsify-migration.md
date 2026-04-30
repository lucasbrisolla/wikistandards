# Wiki Standards Docsify Migration Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Publicar a Wiki Standards em um repositorio Docsify limpo, com foco inicial no acervo `Markdown/` e navegacao por familia.

**Architecture:** O site continua na raiz do template Docsify, com `README.md`, `_sidebar.md` e `index.html` como camada de navegacao. O acervo `Markdown/` e paginas de familia sao adicionados sem alterar o corpo das normas.

**Tech Stack:** Docsify, Markdown, GitHub Pages

---

### Task 1: Preparar a base do site

**Files:**
- Modify: `README.md`
- Modify: `_sidebar.md`
- Modify: `index.html`

- [ ] Substituir os placeholders do template pelo branding e navegacao inicial da Wiki Standards.
- [ ] Ajustar o `index.html` para usar nome, descricao e busca em portugues.

### Task 2: Publicar o acervo Markdown

**Files:**
- Create: `Markdown/`

- [ ] Copiar o acervo `Markdown/` da biblioteca de origem para o repositorio publicado.
- [ ] Preservar nomes de arquivos e subpastas para reduzir risco de links quebrados.

### Task 3: Criar paginas de navegacao por familia

**Files:**
- Create: `families/cpcs.md`
- Create: `families/icpcs.md`
- Create: `families/nbc-ta-cta.md`
- Create: `families/nbc-tg-itg-ctg-otg.md`
- Create: `families/nbc-ti.md`

- [ ] Criar uma pagina de entrada por familia.
- [ ] Listar todas as normas da familia com links para os arquivos em `Markdown/`.
- [ ] Manter a sidebar enxuta, deixando a listagem completa dentro de cada familia.

### Task 4: Verificar o resultado

**Files:**
- Verify: `README.md`
- Verify: `_sidebar.md`
- Verify: `families/*.md`
- Verify: `Markdown/`

- [ ] Validar a estrutura de arquivos criada.
- [ ] Conferir links e contagem de arquivos por familia.
- [ ] Rodar um servidor local simples para inspecionar a navegacao.
