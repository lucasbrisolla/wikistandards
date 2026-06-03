---
name: revisao-editorial-normas
description: Revisar editorialmente normas em Markdown no repositório `wikistandards`, com PDF como fonte de verdade e foco em headings, listas, quebras de linha, tachados confirmados visualmente e fidelidade ao texto normativo. Use quando Codex precisar editar arquivos como `normas/CPCs/*.md`, `normas/ICPCs/*.md` ou correlatos, validar leitura no site local, e atualizar a `LISTA-MESTRA-ESCOPO-EDITORIAL.md` ao concluir um arquivo.
---

# Revisao Editorial Normas

Use esta skill para trabalho editorial recorrente no repositório `/home/lucas/wikistandards`.

## Fluxo obrigatório

1. Trabalhar no repositório correto: `/home/lucas/wikistandards`.
2. Não redescobrir o projeto nem procurar outra pasta-base se o usuário já indicou `wikistandards`.
3. Não usar clones ou cópias no Vault, como `3. Arquivos/Wiki Standards`, salvo pedido explícito do usuário.
4. Verificar no início se já existe servidor local ativo em `http://127.0.0.1:3000`.
5. Se não existir e a tarefa for editorial, subir o preview local antes de validar leitura.
6. Ler o Markdown atual do arquivo alvo.
7. Comparar com o PDF original como fonte principal de verdade.
8. Usar DOCX apenas como apoio para recuperar estrutura, listas ou trechos corrompidos.
9. Corrigir o arquivo sem alterar o sentido normativo.
10. Ao concluir o arquivo, marcar automaticamente o item correspondente em `LISTA-MESTRA-ESCOPO-EDITORIAL.md`.

## Regras editoriais

- Não reescrever frases por estilo.
- Não resumir conteúdo normativo.
- Não “melhorar” redação jurídica ou técnica.
- Remover os blocos iniciais de `Termos de uso` e `Notice`, salvo instrução explícita em contrário.
- Preservar texto tachado com `<del>...</del>` somente quando o tachado puder ser confirmado visualmente no PDF.
- Não inferir tachado apenas pelo texto extraído.
- Ajustar apenas:
  - headings
  - listas e alíneas
  - quebras de linha ruins
  - espaçamentos corrompidos
  - tabelas ou blocos quebrados pela conversão
  - estrutura editorial para leitura no Docsify

## Hierarquia padrão

- Usar o sumário do documento como referência principal de hierarquia.
- Converter entradas principais em maiúsculas para `##`.
- Converter subtítulos subordinados em minúsculas para `###`.
- Descer além disso só quando o documento mostrar subdivisão real.
- Reservar `#` para o título principal da norma quando o padrão do repositório não usar `standard-header`.
- Quando o arquivo já seguir o padrão visual novo do repositório, preferir:
  - bloco `<div class="standard-header">`
  - `<h1 class="standard-title">`
  - `<p class="standard-summary">`

## Modelos de referência

- Usar `/home/lucas/wikistandards/normas/CPCs/CPC_51.md` como principal referência de estrutura limpa e padrão visual atual.
- Usar `/home/lucas/wikistandards/normas/ICPCs/ICPC_22.md` como referência de `ICPC` concluído com boa hierarquia, listas e apêndices.
- Usar `/home/lucas/wikistandards/normas/ICPCs/ICPC_23.md` como referência de `ICPC` curto já concluído.
- Quando houver conflito entre modelo e PDF, seguir o PDF.

## Listas e alíneas

- Preferir `- (a)`, `- (b)` etc. para alíneas quando isso melhorar a leitura no Docsify.
- Para subalíneas, usar `- (i)`, `- (ii)` etc.
- Corrigir listas numeradas corrompidas pela conversão, como `3. (a)` ou `6. (b)`, quando na verdade forem alíneas do item anterior.

## Tachados

- Sempre confirmar visualmente no PDF antes de aplicar `<del>`.
- Se necessário, converter o PDF em imagem para inspeção visual.
- Se não houver confirmação visual, manter o texto sem tachado e registrar a dúvida ao usuário.

## Arquivos de controle

- Atualizar automaticamente `LISTA-MESTRA-ESCOPO-EDITORIAL.md` quando um arquivo for concluído.
- Não atualizar `CONTROLE-EDITORIAL.md` nem `BACKLOG.md`, salvo pedido explícito.

## Checklist de saída

- Confirmar que o arquivo revisado está no repositório correto.
- Confirmar que nenhum clone paralelo ou cópia do Vault foi usado por engano.
- Confirmar que headings e sumário ficaram coerentes.
- Confirmar que tachados só foram marcados com validação visual.
- Confirmar se o item da lista mestra foi marcado.
- Resumir exatamente o que foi ajustado.
