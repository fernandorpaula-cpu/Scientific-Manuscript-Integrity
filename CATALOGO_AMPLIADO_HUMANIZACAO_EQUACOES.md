# Prompts de humanização, equações e escrita didática — inventário ampliado

**Data:** 2026-10-23. **Escopo:** manuscritos científicos; escrita, didática, matemática, integridade e revisão.

## A. Humanização / prosa / autoria (origens verificadas)

| Identificação | Fonte | Função comprovada | Relação de versão |
|---|---|---|---|
| `humanizador.docx` — `/human-scientific` | Google Drive, arquivo lido | Reconstrução editorial contínua; congela equações, dados, unidades, referências, resultados negativos e limites | Parente próximo do HSEF-2, **não assumir equivalência textual** |
| `HUMAN_SCIENTIFIC_Melhor.md` | Google Drive, arquivo lido | HSEF-2 v2; modos `/deep`, `/conservative`, `/final`, `/journal`, `/discipline` | Texto inicial idêntico ao `HUMAN_SCIENTIFIC_V2_HSEF2.md` encontrado |
| `HUMAN_SCIENTIFIC_V2_HSEF2.md` | Google Drive, arquivo lido; também Biblioteca ChatGPT | Humanização científica com bloqueio de drift de conteúdo | Canônico geral v2 |
| `HSEF2_PROTOCOL.md` | Google Drive, arquivo lido | HSEF-2 | Cópia com mesmo tamanho e conteúdo recuperado |
| `10_HUMAN_SCIENTIFIC_HSEF2.md` | Drive/GitHub | Fase de pipeline editorial | Adaptador, não confundir com o texto integral v2 |
| `HUMAN_SCIENTIFIC_V3_DNA_PCL_PVP_RP_CUR.md` | Drive, metadados confirmados | Revisão especializada em manuscrito PCL/PVP/Curcuma | Variante por artigo, não substitui v2 geral |
| `HUMAN_SCIENTIFIC_V3_AUDIT_REPORT.md` | Drive, metadados confirmados | Relatório da aplicação v3 | **Relatório**, não prompt |
| `Scientific_Biomaterials_FRP` | Histórico de personalização Grammarly | Perfil de escrita científica para biomateriais; revisão de Introduction, Results/Discussion, Conclusion | Configuração editorial, arquivo canônico não recuperado |
| `scientific-authorial-writing` | Histórico de desenvolvimento | Skill/GPT autoral; modos revisão conservadora, profunda, reconstrução, análise de artificialidade, perfil autoral | Referência histórica, fonte não recuperada nesta rodada |
| `PROMPT 37 — Human Scientific Final` | Drive, produtos de execução identificados | Polimento final pós-auditoria | Instância de projeto, não duplicar HSEF-2 como nova família |

## B. Equações, formalismo e redação matemática

| Identificação | Fonte | Uso |
|---|---|---|
| `MATHMEM_PLUS_MASTER_PROMPT.md` | GitHub privado e Biblioteca | Derivações, transferência de mecanismos, controles independentes e contraexemplos |
| `prompts/MATHMEM_PLUS.md` | GitHub privado | Adaptador de execução matemática |
| `LEMA.md` | GitHub privado | Engenharia reversa e reconstrução de demonstrações de manuscritos |
| `PROMPT_MESTRE_ARTIGO_TEORICO_DIDATICO_EQUACOES.md` | Biblioteca ChatGPT, arquivo original localizado | Exposição didática progressiva de equações, com cada passagem justificada; corpo canônico disponível na Biblioteca |
| `PROMPT_MESTRE_ARTIGO_TEORICO_DIDATICO_EQUACOES(2).md` | Histórico de 2026-09-27 | Variação/cópia da família anterior, não tratar como novo prompt |
| `PROMPT_MESTRE_ARTIGO_TEORICO_DIDATICO_FINAL_DNA_FIRST.md` | Drive e GitHub, texto lido | Problema → hipóteses → definições → formalismo → derivação → resultado → interpretação → validade → consequência |
| `08_DIDATICO_DNA_FIRST.md` | Drive, pasta `PROMPTS_ARTIGOS` | Oitava etapa do pipeline canônico |
| `Prompt_04_Reconstrucao_Matematica_e_Equacoes.md` | Drive, metadados confirmados | Reconstrução matemática e equações; conteúdo integral pendente |
| `equacoes_revisadas_P20.md` | Drive, metadados confirmados | Artefato de revisão de equações, **não necessariamente prompt** |
| `Prompt_03_Transcricao_Integral_do_Texto.md` | Drive, metadados confirmados | Preservação/transcrição integral do texto |
| `prompt_reconstrucao_robusta_artigo_latex.md` | Drive, metadados confirmados | Reconstrução robusta em LaTeX, verificar versão canônica |
| `prompt_latex_ingles_para_portugues.md` | Drive, metadados confirmados | Tradução de manuscrito LaTeX |
| `prompt_conversao_docx_equacoes_editaveis.pdf` | Drive, metadados confirmados | Conversão de fórmulas para DOCX editável |
| `LATEX_TO_DOCX_STRICT_FIDELITY_PROTOCOL.md` | Drive, metadados confirmados | Preservar LaTeX canônico e conferir equações, referências, tabelas e imagens no DOCX |

## C. Estrutura, narrativa, integridade e artigos longos

| Identificação | Fonte | Papel |
|---|---|---|
| `PROMPTS_NARRATIVA_CONTINUA_SEM_REDUCAO_2026-09-29.md` | Biblioteca ChatGPT, arquivo original localizado | Reescrita da narrativa com preservação de conteúdo; corpo disponível na Biblioteca |
| `09_NARRATIVA_CONTINUA_SEM_REDUCAO.md` | Drive/GitHub | Fase 09 do pipeline |
| `11_SCIENTIFIC_DIFF_CLAIM_DRIFT_FIREWALL.md` | Drive | Comparação científica antes/depois; bloqueia deriva de claims |
| `SCIENTIFIC_DIFF.md` | Drive | Ferramenta/protocolo relacionado à comparação |
| `prompt_auditoria_manuscrito.md` v2.1 | Drive, texto lido | Inspeção de figuras, tabelas, referências, números, unidades e chamadas cruzadas |
| `PROMPT_MESTRE_AVALIACAO_ARTIGO_P00_P15.md` | Biblioteca | Gate sequencial completo |
| `REFERIS_PROTOCOL.md` | Biblioteca | Arbitragem científica adversarial independente |
| `REFEREE_V2_PROTOCOL.md` | Biblioteca/Drive | Parecer científico multi-referee |
| `REFEREE_REDTEAM_V2.md` | Drive, metadados | Instância red-team |
| `PROMPTS_R90_MULTIAAGENTES.md` | GitHub privado | Multiagentes/avaliação integral de ciência |
| `CONJETRA_PROMPT_MESTRE.txt` | GitHub privado | Hipóteses, conjecturas e falsificação |
| `RADAR_CIENTIFICO_PROMPT_UNICO_V4.md` | Drive, metadados | Busca e anterioridade científica |
| `REPOSITORY_GITHUB_ZENODO_DEPOSITION` | Histórico | Deposição e reprodutibilidade; fonte exata pendente |
| `Scientific Submission Freeze` | Histórico/Drive | Travamento editorial, empacotamento e decisão GO/NO-GO |

## D. Pipeline canônico de 18 prompts (lista integral de arquivos confirmada)

**Fonte:** Google Drive, pasta `PROMPTS_ARTIGOS`, com 18 documentos `.md` e guia PDF; **não são 18 nomes inventados ou 18 projetos independentes**.

| Ordem | Arquivo | Fase |
|---|---|---|
| 01 | `01_MASTER_AUDITORIA_REDUCAO_RISCO.md` | Diagnóstico de risco científico |
| 02 | `02_LITERATURE_PRIOR_ART_NOVELTY_FIREWALL.md` | Anterioridade/novidade |
| 03 | `03_DOMAIN_SCIENTIFIC_AUDIT.md` | Auditoria científica do domínio |
| 04 | `04_MATH_METHODS_NUMERICS_STATISTICS_AUDIT.md` | Matemática, métodos, numerics, estatística |
| 05 | `05_REPRODUCIBILITY_TRACEABILITY_AUDIT.md` | Reprodutibilidade |
| 06 | `06_SCIENTIFIC_REPAIR_INDEPENDENT_RETEST.md` | Reparo + reteste independente |
| 07 | `07_SCIENTIFIC_FREEZE.md` | Congelamento de resultados |
| 08 | `08_DIDATICO_DNA_FIRST.md` | Progressão didática |
| 09 | `09_NARRATIVA_CONTINUA_SEM_REDUCAO.md` | Coesão sem cortes |
| 10 | `10_HUMAN_SCIENTIFIC_HSEF2.md` | Escrita científica autoral |
| 11 | `11_SCIENTIFIC_DIFF_CLAIM_DRIFT_FIREWALL.md` | Verificação das mudanças |
| 12 | `12_REFEREE_V2_FULL.md` | Parecer adversarial |
| 13 | `13_TARGET_JOURNAL_READINESS.md` | Revista-alvo |
| 14 | `14_FIGURES_TABLES_VISUAL_QA.md` | Figuras e tabelas |
| 15 | `15_GITHUB_ZENODO_REPRODUCIBILITY_PACKAGE.md` | Proveniência e pacote |
| 16 | `16_FINAL_SUBMISSION_PREFLIGHT_GO_NOGO.md` | Gate pré-submissão |
| 17 | `17_LATEX_TO_DOCX_STRICT_FIDELITY.md` | Transcodificação |
| 18 | `18_DOCX_FIDELITY_POSTCHECK.md` | Verificação de fidelidade DOCX |

**Regra operacional do guia:** `AUDIT → ISSUES → REPAIR → INDEPENDENT RETEST → PASS → NEXT`. Após a etapa 07, qualquer alteração exige verificação por `SCIENTIFIC DIFF`.

## E. Outros pacotes de prompts identificados no Drive

- `MASTER_ORCHESTRATOR.md` e `P00_FREEZE_PROVENANCE.md` a `P14_JOURNAL_SCOPE.md`: pacote de **15 fases P00–P14** além do orquestrador, separado do pipeline canônico de 18.
- `P00_FREEZE_AND_CHANGE_MAP.md` a `P08_BUILD_AR15_FINAL.md`: pacote **AR15** com controle de hipóteses, atualização literária e `P06_STRUCTURE_AND_PEDAGOGY.md`.
- `00_MASTER_AR15_INTEGRATION.md`, `00_MASTER_RECONSTRUCTION.md`, `01_G09_PHYSICS_INTEGRATION.md` a `09_COMPILE_AND_FINAL_AUDIT.md`: pacote de reconstrução, literatura, referências, reestruturação LaTeX e compilação.
- `PROMPTS_COMPLETOS.md`: contém **dez fases P00–P09 relacionadas ao projeto MATHMEM Buder/Splash**; não confundir com biblioteca geral de todos os prompts.
- `ALL_PRD_PROMPTS.md`: coleção específica para conversão do manuscrito *Fixed-Slice Spectral Obstructions* ao padrão Physical Review D.

## F. Como usar as famílias no Scientific Manuscript Integrity

As famílias **não devem ser aplicadas indiscriminadamente em uma única passagem**. Proposta por camadas:

1. `AUDIT_RISK + RADAR + NOVELTY`: evidência e originalidade.
2. `LEMA + MATHMEM + EQUATIONS_DIDACTIC`: validar e explicar formalismo.
3. `DNA_FIRST + NARRATIVE_CONTINUOUS + HSEF2`: didática, organização e prosa.
4. `SCIENTIFIC_DIFF + REFEREE/REFERIS`: revisão adversarial independente.
5. `FIGURES_QA + SUBMISSION_FREEZE + DOCX_FIDELITY`: pacote final.

### Notas de fidelidade

- Os protocolos `humanizador.docx` e HSEF-2 são **edição científica conservadora**, não garantias de burlar detecção de IA.
- Uma derivação matemática mais didática **não autoriza** mudar equações ou preencher passagens não demonstradas sem marcar explicitamente uma proposta matemática nova.
- Os relatórios e variantes de artigos específicos **não são automaticamente prompts universais**.
- O destino GitHub atualmente **público** contém **somente este inventário**, não cópias integrais de documentos privados.
- O termo “todos” fica condicionado à acessibilidade, deduplicação e revisão de eventuais outras pastas/arquivos locais não varridos.

## G. Reavaliação de fontes (após busca específica na Biblioteca)

**Recuperados integralmente como arquivos localizáveis, sem migração do conteúdo para o repositório público:**

- `PROMPT_MESTRE_ARTIGO_TEORICO_DIDATICO_EQUACOES.md` — fonte original encontrada na Biblioteca. A seção “Regra de progressão pedagógica” exige motivação, definição dos objetos e derivação sequencial verificável. A versão `(2)` continua sendo tratada como variante/cópia até diff.
- `PROMPTS_NARRATIVA_CONTINUA_SEM_REDUCAO_2026-09-29.md` — fonte original encontrada na Biblioteca; existe cópia `(1)`. Restringe cortes e exige preservação da estrutura científica.
- `LATEX_TO_DOCX_STRICT_FIDELITY_PROTOCOL.md` — original e cópia `(1)` encontrados na Biblioteca. Checagem estrutural e matemática da conversão para DOCX.

Este complemento melhora o estado de proveniência dos três protocolos, **não comprova equivalência entre suas variantes**.
