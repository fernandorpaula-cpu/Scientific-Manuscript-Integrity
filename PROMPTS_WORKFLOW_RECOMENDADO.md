# Orquestração de prompts para manuscritos científicos

**Proposta SMI (nova, 2026-10-23).** Este arquivo **não se apresenta como um dos prompts originais** encontrados nos repositórios do pesquisador. É um protocolo de integração para artigos, teses e dissertações.

## Princípios não negociáveis
- O arquivo original é imutável; cada revisão tem SHA-256 e `diff`.
- O objetivo é melhorar precisão, legibilidade, didática e integridade, **não evadir detectores de IA**.
- Equações, observáveis, variáveis, números, incertezas, unidades, tabelas, figuras, referências e intensidade epistemológica exigem bloqueio e comparação.
- Mudança substantiva requer justificativa científica, evidência, autor e aprovação humana.
- Falha de rede, indisponibilidade de bibliografia ou falta de dados conduz a `BLOCKED`, jamais a invenção.
- Um parecer simulado por LLM não substitui arbitragem por pares.

## Modos do orquestrador

### 1. Edição textual conservadora
`Scientific Freeze → HUMAN_SCIENTIFIC HSEF-2 (/conservative) → SCIENTIFIC_DIFF → LanguageTool/LTeX+ → aprovação`.

**Entrada:** `.tex`, `.docx` (preservar OOXML), PDF em inspeção. **Saída:** propostas de edição com localização/justificativa e uma cópia separada. **Proibição:** editar ciência ou sobrescrever originais.

### 2. Texto teórico com equações didáticas
`LEMA → MATHMEM Plus → DNA-FIRST → DIDATICO_EQUACOES → HUMAN_SCIENTIFIC (/deep) → SCIENTIFIC_DIFF → REFEREE v2`.

**Contrato por resultado:** hipótese, definições, expressão inicial, identidades usadas, passagens justificadas, aproximações, limites, interpretação e domínio de validade. **Separar** identidade formal comprovada, teste numérico, conjectura e interpretação física. Ninguém pode completar uma lacuna formal sem registrar hipótese nova.

### 3. Artigo experimental
`AUDITORIA DE DOMÍNIO → REPRODUCIBILITY/TRACEABILITY → FIGURES/TABLES QA → DOI/BIBLIOGRAPHY QA → DNA-FIRST/HSEF-2 → REFEREE v2 → Submission Freeze`.

**Regra:** ausência de dados brutos bloqueia claims de reprodutibilidade e proíbe gerar figuras que se passem por experimentos.

### 4. Novo artigo e originalidade
`RADAR Plus → CONJETRA → LEMA/MATHMEM → testes adversariais → SRE-TRIAD → pré-manuscrito → REFERIS/REFEREE v2`.

**Regra:** literatura revisada e testes falsificáveis precedem alegações de novidade.

### 5. Tese / dissertação longa
Aplicar os 18 prompts canônicos **com checkpoints por capítulo**, mais registros globais de glossário, símbolos, datasets, `.bib`, decisões de revisão e referências cruzadas. Preservar a versão-fonte de cada capítulo; índices e sumário consolidados devem ser testados após a junção.

## Interface sugerida para os adaptadores
```json
{
  "prompt_id": "HUMAN_SCIENTIFIC_V2_HSEF2",
  "origin": "Google Drive / GitHub private",
  "source_verified": true,
  "source_hash": "PENDING",
  "input_file": "chapter_01.tex",
  "mode": "conservative",
  "read_only": true,
  "preserve": ["math","citations","numbers","units","claims","figures","tables"],
  "expected_outputs": ["suggestions.json","scientific_diff.json","decision.md"],
  "gate": "BLOCKED_UNTIL_APPROVED"
}
```

## Critérios de aceitação
- Sem mudanças numéricas, matemáticas, bibliográficas ou inferenciais não aprovadas.
- Nenhum relatório afirma teste/consulta externa sem log de execução real.
- Cada correção é reversível, rastreável e revisável por humano.
- Documentos não originais ou parciais permanecem marcados `INCOMPLETE_SOURCE`.
- O sistema não equipara “humanização” com redução de rastros de IA.
- Nenhuma chamada de modelo substitui verificação simbólica e numérica quando necessária.

## Escopo do SMI hoje

Este workflow é uma **especificação de integração**; não documenta execução real de todos os módulos. A implementação do SMI v1.0 é um protótipo separado, sem integração completa de todos os prompts e ferramentas.

Ver [catálogo de origem](CATALOGO_PROMPTS_CIENTIFICOS.md), [complemento humanização/equações](CATALOGO_AMPLIADO_HUMANIZACAO_EQUACOES.md).
