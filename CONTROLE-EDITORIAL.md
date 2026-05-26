# Controle Editorial

Controle de avanço da revisão editorial das normas publicadas no `Wiki Standards`.

Objetivo:
- acompanhar a aplicação do novo padrão visual e estrutural
- identificar famílias prioritárias
- registrar pilotos concluídos e frentes ainda não iniciadas

## Legenda

- `Não iniciado`: arquivo ainda no formato bruto de conversão
- `Parcial`: arquivo com ajustes pontuais, mas sem revisão editorial completa
- `Piloto`: arquivo revisado como referência de padrão
- `Concluído`: arquivo revisado de ponta a ponta no padrão editorial adotado

## Padrão editorial de referência

Usar como referência o trabalho aplicado em `CPC 51`:
- topo editorial legível
- headings alinhados ao sumário original
- alíneas e subalíneas reconstruídas em Markdown limpo
- sumários/apêndices reestruturados quando a conversão estiver corrompida
- legibilidade priorizada sobre fidelidade visual bruta ao PDF

## Resumo por família

| Família | Qtde. | Prioridade | Situação geral | Observação |
|---|---:|---|---|---|
| CPCs | 53 | Alta | Em andamento | `CPC 51` concluído como piloto e referência |
| ICPCs | 23 | Média | Não iniciado | Boa candidata para segunda onda |
| NBC TA/CTA | 68 | Média | Não iniciado | Normas longas e úteis para testar TOC |
| NBC TG/ITG/CTG/OTG | 70 | Alta | Não iniciado | Acervo grande, provável maior esforço editorial |
| NBC TI | 1 | Baixa | Não iniciado | Caso isolado |

## Controle por norma

### CPCs

| Norma | Status | Observação |
|---|---|---|
| CPC 51 | Concluído | Referência atual de estrutura, headings e apêndices |
| CPC 00 | Não iniciado | Prioritária por relevância geral |
| CPC 29 | Não iniciado | Aberta recentemente no fluxo de trabalho |
| CPC 26 | Não iniciado | Alta relevância para apresentação |
| CPC 03 | Não iniciado | Boa candidata para validar tabelas e estrutura |

### ICPCs

| Norma | Status | Observação |
|---|---|---|
| ICPC 01 | Não iniciado | Aberta recentemente no fluxo de trabalho |
| ICPC 02 | Não iniciado | Aberta recentemente no fluxo de trabalho |

### NBC TA/CTA

| Frente | Status | Observação |
|---|---|---|
| Família NBC TA/CTA | Não iniciado | Selecionar 2 a 3 normas-piloto antes de escalar |

### NBC TG/ITG/CTG/OTG

| Frente | Status | Observação |
|---|---|---|
| Família NBC TG/ITG/CTG/OTG | Não iniciado | Provável maior volume e maior necessidade de triagem |

### NBC TI

| Frente | Status | Observação |
|---|---|---|
| RES 986 | Não iniciado | Item isolado |

## Próximas ondas sugeridas

1. Fechar um lote curto de `CPCs` de alta relevância: `CPC 00`, `CPC 26`, `CPC 03`, `CPC 29`
2. Escolher `2` normas de `ICPCs` para validar esforço em documentos menores
3. Escolher `1` norma de `NBC TA/CTA` e `1` de `NBC TG/ITG/CTG/OTG` para medir adaptação do padrão

## Regras de atualização

- Ao iniciar uma norma: mudar para `Parcial`
- Ao usar uma norma como referência de padrão: marcar `Piloto`
- Ao revisar o arquivo inteiro, incluindo apêndices relevantes: marcar `Concluído`
- Sempre registrar observações curtas sobre o tipo de problema encontrado:
  exemplos: `sumário corrompido`, `listas quebradas`, `tabela ruim`, `headings achatados`
