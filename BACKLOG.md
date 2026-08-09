# Backlog

Backlog do site `Wiki Standards`, com foco na experiência de consulta, na clareza editorial e na curadoria visível do acervo publicado.

Além dos ajustes de navegação e edição, este backlog também registra melhorias de operabilidade do produto: entrada canônica, inventário do repositório, diagnóstico rápido e verificações mínimas de drift.

## Base do produto

- [ ] Expandir o `README.md` para uma entrada curta com `O que é`, `Como começar`, `Project Structure`, `O que ele não é` e `Onde está o detalhe`.
- [ ] Criar um `PRODUCT_INDEX.md` na raiz com o inventário navegável do repositório e links para as superfícies principais.
- [ ] Criar um `HEALTH_CHECK.md` ou `STATUS.md` com cobertura por família, pilotos editoriais, lacunas e sinais de drift.
- [ ] Definir verificações automáticas mínimas para links, navegação e páginas-chave.
- [ ] Documentar o fluxo de atualização do índice de busca e a validação cruzada com `_sidebar.md`.
- [ ] Estudar referências de UX como `MDN`, `LII Cornell`, `EUR-Lex` e `NIST` para padronizar status, vigência, histórico e topo editorial.

## Consistência do catálogo

- [ ] Normalizar a indicação de revisão no `cpc-map.md` e nas equivalências, para que a versão vigente apareça de modo consistente em toda a navegação.
- [ ] Explicitar o `CPC 34` como norma `a emitir` nos mapas e índices, se a intenção for manter essa ausência visível no catálogo.
- [ ] Revisar o papel das páginas de família (`families/*.md`) versus os mapas do catálogo, para deixar clara a diferença entre entrada simples e consulta rica.
- [ ] Avaliar se o `standards-index.md` deve ganhar uma coluna simples de `status` ou `escopo` para destacar famílias históricas, revogadas ou pendentes.
- [ ] Avaliar se `ey-good-group-regulacao-contabil-brasileira.md` deve migrar para uma área de apoio mais explícita, separada do índice principal.

## Expansão de fontes

- [ ] Definir uma taxonomia explícita de `tipo de fonte` para orientar futuras expansões: `norma`, `interpretação`, `equivalência`, `regulação setorial` e `apoio editorial`.
- [ ] Avaliar a inclusão de `IFRS Accounting Standards` como família ou trilha separada, se houver interesse em ampliar o acervo para a fonte internacional primária.
- [ ] Avaliar a inclusão de materiais da `IFRS Foundation` como `IFRS Sustainability Disclosure Standards` e `Management Commentary`, deixando claro se entram como normas, apoio ou consulta externa.
- [ ] Avaliar a inclusão de reguladores e fontes setoriais brasileiras, como `CVM` e outros órgãos, apenas se houver separação clara entre norma, ato regulatório e material de apoio.

## Agora

- [ ] Padronizar o topo das normas com um modelo editorial consistente em todo o acervo.
  Referência atual: piloto aplicado no `CPC 51` com código da norma, título legível e linha curta de apoio.
- [x] Aplicar linhas divisórias discretas abaixo do título principal (`h1`) para reforçar hierarquia visual.
- [ ] Revisar a barra de busca no tema escuro para garantir aderência completa à paleta da página.
- [ ] Refinar o comportamento da busca para priorizar melhor código exato, título e equivalências.
- [ ] Criar um atalho de teclado `"/"` para focar a busca do catálogo e documentar esse fluxo.
- [ ] Deixar os resultados da busca mais contextuais, no estilo `DocSearch`, com tipo, trecho e página de origem mais visíveis.
- [ ] Validar a home e os cards em telas pequenas para evitar overflow e desalinhamentos.
- [ ] Aplicar o padrão editorial do `CPC 51` nas normas mais acessadas.
- [ ] Corrigir headings, sumários e listas corrompidos por conversão nas normas prioritárias.
- [ ] Definir uma profundidade-padrão da TOC da direita para normas longas.
- [ ] Automatizar ou documentar a atualização do `cacheBuster` do `index.html` a cada publicação.

## Próximo

- [ ] Criar uma página de siglas (`CPC`, `ICPC`, `NBC TG`, `NBC TA`, `ITG`, `CTG`, `IFRS`).
- [ ] Adicionar metadados discretos em páginas-chave, como `Família`, `IFRS correlata` e `Atualizado em`.
- [ ] Inserir links relacionados ao fim das consultas e páginas de curadoria.
- [ ] Revisar títulos em caixa alta nas normas mais acessadas e alinhar a hierarquia com o sumário original.
- [x] Tornar os resultados de busca mais autoexplicativos com tipo do resultado (`Norma`, `Consulta`, `Equivalência`).
- [ ] Tratar notices, termos de uso e notas finais com uma regra editorial consistente de legibilidade.
- [ ] Testar um fluxo reutilizável de reconstrução editorial com apoio de `PDF` e `DOCX`.
- [ ] Avaliar um piloto com `pdf-inspector` para classificar PDFs e gerar Markdown preliminar localmente, mantendo OCR, conferência visual e revisão humana para os casos de baixa confiabilidade.

## Depois

- [ ] Destacar normas mais procuradas na home ou nas consultas por família.
- [ ] Criar uma página curta de metodologia explicando como as equivalências foram organizadas.
- [ ] Adicionar estados vazios melhores na busca, com sugestões quando não houver correspondência direta.
- [ ] Considerar uma versão móvel própria da busca, em vez de depender do mesmo comportamento do desktop.
- [ ] Avaliar se vale mostrar `Última atualização` por página de catálogo.

## Observações

- O backlog do repositório publicado deve permanecer mais enxuto e voltado ao uso do site.
- O backlog arquitetural e de expansão do acervo maior pode continuar separado no vault principal.
- O acompanhamento de revisão norma por norma deve ficar no arquivo [`CONTROLE-EDITORIAL.md`](CONTROLE-EDITORIAL.md).
