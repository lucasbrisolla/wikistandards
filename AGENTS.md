# AGENTS.md

Instruções canônicas para agentes que trabalhem neste repositório.

## Escopo

- Este repositório de trabalho é `/home/lucas/wikistandards`.
- Não use clones, espelhos ou cópias no Vault como base de trabalho, salvo pedido explícito do usuário.
- Considere `AGENTS.md` a fonte canônica de instruções do repositório.

## Objetivo do projeto

- Preservar textos normativos em Markdown para consulta.
- Organizar navegação auxiliar sem reescrever o conteúdo normativo.
- Manter coerência entre `normas/`, `catalogo/`, `families/` e artefatos de apoio.

## Estrutura principal

- `normas/`: textos normativos.
- `catalogo/`: índices, mapas e equivalências.
- `families/`: agrupamentos por família normativa.
- `skills/`: skills locais de apoio ao fluxo editorial e de documentação.

## Regras operacionais

- Trabalhe diretamente neste repositório.
- Não faça redescoberta do projeto se o usuário já tiver indicado `wikistandards`.
- Preserve alterações locais do usuário; nunca reverta mudanças não solicitadas.
- Siga os padrões já existentes do repositório antes de introduzir nova estrutura.
- Mantenha mudanças focadas no pedido atual.

## Regras editoriais

- Não reescreva texto normativo por estilo.
- Não resuma nem altere o sentido jurídico ou técnico.
- Em caso de conflito entre material auxiliar e a norma, priorize a fonte normativa indicada pelo fluxo da tarefa.
- Ajustes editoriais devem se limitar ao necessário para preservar estrutura, legibilidade e fidelidade.

## Sessões editoriais

- Em sessões de revisão editorial, não saia procurando arquivos por conta própria para decidir o que revisar.
- Abra o arquivo Markdown alvo e os arquivos de apoio somente quando o usuário informar explicitamente os caminhos, salvo instrução contrária.
- Se o usuário não informar o caminho do arquivo alvo ou dos apoios, peça os caminhos em vez de procurar.
- Quando a tarefa for editorial, consulte `PROMPT-EDITORIAL-SESSAO.md`.
- Quando a tarefa pedir revisão editorial de normas, use a skill local `skills/revisao-editorial-normas/SKILL.md`.

## Prioridade entre instruções

- Instruções diretas do usuário têm prioridade máxima.
- Depois, siga este `AGENTS.md`.
- Para tarefas editoriais, aplique o fluxo específico do prompt e da skill correspondente.

## Arquivos relacionados

- `PROMPT-EDITORIAL-SESSAO.md`: prompt curto para iniciar sessões editoriais.
- `skills/revisao-editorial-normas/SKILL.md`: fluxo editorial detalhado para revisão de normas.
