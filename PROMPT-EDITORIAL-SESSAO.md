# Prompt Editorial de Sessão

Use este prompt como ponto de partida em novas sessões para continuar a revisão editorial das normas em Markdown no repositório `wikistandards`.

```text
Vamos continuar o trabalho editorial no repositório `/home/lucas/wikistandards`.

Objetivo desta sessão:
revisar e melhorar a estrutura de arquivos Markdown de normas, priorizando legibilidade, hierarquia de headings e reconstrução fiel da conversão, sem alterar o sentido do texto normativo.

Regras editoriais obrigatórias:
- a fonte de verdade principal é o PDF original
- o DOCX pode ser usado como apoio para recuperar estrutura e listas
- o Markdown atual é apenas a base de trabalho do site
- não reescreva frases por estilo
- não resuma conteúdo normativo
- não “melhore” a redação jurídica/técnica
- remover os blocos iniciais de `Termos de uso` e `Notice`, salvo se eu pedir explicitamente para mantê-los
- quando o PDF mostrar texto tachado/riscado, preservar isso no Markdown com `<del>...</del>`
- só aplicar `<del>...</del>` quando o tachado puder ser confirmado visualmente no PDF; não inferir isso apenas a partir de texto extraído
- só ajuste:
  - headings
  - listas e alíneas
  - quebras de linha ruins
  - espaçamentos corrompidos
  - blocos/tabelas claramente quebrados pela conversão
  - estrutura editorial para leitura no Docsify
- qualquer reconstrução textual deve buscar restaurar o que está no PDF, não inventar formulação nova

Padrão de hierarquia:
- `#` reservado ao título da norma, quando aplicável
- `##` para seções principais
- `###` para subseções
- `####` e `#####` apenas quando realmente necessário
- usar o sumário do documento como referência de hierarquia sempre que possível
- no sumário, entradas em letras maiúsculas indicam título/seção principal; entradas em letras minúsculas indicam subtítulo/subseção
- ao converter a hierarquia do sumário para Markdown, preferir:
  - entrada principal em maiúsculas -> `##`
  - entrada subordinada em minúsculas sob essa principal -> `###`
  - só descer além disso quando o próprio documento mostrar uma subdivisão real

Padrão de listas:
- para alíneas, preferir `- (a)`, `- (b)` etc. quando isso renderizar melhor no Docsify
- para subalíneas, usar recuo com `- (i)`, `- (ii)` etc.
- evitar HTML/CSS embutido no Markdown

Padrão visual/editorial já adotado:
- usar `CPC 51` como referência de estrutura limpa
- priorizar legibilidade no site
- respeitar PT-BR em títulos, rótulos e arquivos auxiliares

Fluxo de trabalho:
1. ler o trecho atual do Markdown
2. comparar com o PDF original
3. quando houver redações sobrepostas, revisadas ou possivelmente revogadas, verificar visualmente se há tachado no PDF antes de decidir a marcação no Markdown
4. usar o DOCX apenas como apoio, se necessário
5. corrigir o trecho solicitado
6. manter o arquivo em Markdown limpo
7. ao concluir um arquivo, marcar automaticamente esse arquivo como concluído em `/home/lucas/wikistandards/LISTA-MESTRA-ESCOPO-EDITORIAL.md`, sem depender de solicitação adicional
8. ao final, resumir exatamente o que foi ajustado
9. não fazer commit nem push, a menos que eu peça

Arquivos de controle:
- atualizar `/home/lucas/wikistandards/CONTROLE-EDITORIAL.md` apenas se eu pedir
- atualizar `/home/lucas/wikistandards/BACKLOG.md` apenas se eu pedir
- atualizar `/home/lucas/wikistandards/LISTA-MESTRA-ESCOPO-EDITORIAL.md` automaticamente quando um arquivo for concluído

Quando houver ambiguidade:
- siga o PDF
- se ainda houver dúvida real, me aponte o ponto exato

Nesta sessão, quero trabalhar neste arquivo:
`[COLE O CAMINHO AQUI]`

Se houver arquivos de apoio, use estes:
- PDF: `[COLE O CAMINHO AQUI]`
- DOCX: `[COLE O CAMINHO AQUI]`

Trecho ou seção a revisar nesta sessão:
`[EX.: itens 21–50 / Apêndice A / seção Balanço Patrimonial]`
```
