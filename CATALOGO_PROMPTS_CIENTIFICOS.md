# Catálogo de prompts científicos — inventário auditável

> Atualização: **2026-10-23**. Catálogo de **arquivos identificados**, famílias canônicas e menções históricas. Não confundir nome encontrado com prompt integral validado ou já executado.

## 1. Protocolos nucleares priorizados

| Nome | Finalidade | Prioridade | Fonte rastreável |
|---|---|---|---|
| MATHMEM Plus | Validação matemática, derivações e contraexemplos | Crítica | GitHub: Scientific-Research-Engineer/prompts/MATHMEM_PLUS.md; mestre original no mesmo repositório |
| REFERIS | Pareceres independentes por especialistas simulados | Crítica | Biblioteca: REFERIS_PROTOCOL.md |
| REFEREE v2.0 | Multi-referee adversarial com meta-editor e aceite | Crítica | Biblioteca: REFEREE_V2_PROTOCOL.md |
| HUMAN-SCIENTIFIC v2 HSEF-2 | Redação científica sem alterar resultados | Crítica | GitHub e Biblioteca: HUMAN_SCIENTIFIC_V2_HSEF2.md |
| HUMAN-SCIENTIFIC v3 DNA | Revisão adaptada ao manuscrito, não protocolo universal validado | Alta | Drive: HUMAN_SCIENTIFIC_V3_DNA_PCL_PVP_RP_CUR.md |
| LEMA | Leitura e reconstrução de provas/manuscritos | Alta | GitHub: Scientific-Research-Engineer/prompts/LEMA.md |
| CONJETRA | Construção e refutação precoce de conjecturas | Alta | GitHub: Scientific-Research-Engineer/prompts/CONJETRA.md |
| RADAR Plus | Busca, anterioridade, portfólio e pré-manuscrito | Crítica | GitHub: Radar-Plus/prompts/phases/ |
| SRE-TRIAD | Validação de afirmações e red-team de teoria | Alta | GitHub: SRE-TRIAD-Scientific-Research-Engine-/prompts/ |
| DNA-FIRST | Estrutura narrativa baseada no DNA científico | Alta | GitHub: Scientific-Research-Engineer/prompts/originais/ |
| BIO MASTER | Pesquisas de biologia e protocolos experimentais | Alta | GitHub: Bio/prompts/ |
| Submission Freeze / P12 | Revisão final de evidência, LaTeX, referências e submissão | Crítica | Biblioteca: P12_FINAL_SUBMISSION_FREEZE.md |
| SMI — PROMPT_CODEX | Engenharia e validação do repositório de auditoria | Alta | Pacote local SMI v1.0/docs/PROMPT_CODEX.md |
| SMI — PROMPT_CODEX_G13_G20 | Evolução de adaptadores e critérios de aceitação | Alta | Pacote local SMI v1.0/docs/PROMPT_CODEX_G13_G20.md |

**Identificação corrigida:** “Matchman” foi localizado como **MATHMEM Plus** nas fontes acessíveis. **REFERIS** e **REFEREE v2.0** são protocolos distintos ou de gerações relacionadas e não devem ser fundidos sem comparação textual.

## 2. Inventário de arquivos em repositórios GitHub acessíveis

Foram varridas as árvores Git do branch `main` em seis repositórios, procurando a pasta `prompts/`, arquivos `PROMPT_*` e dois documentos suplementares de execução. Os caminhos abaixo são confirmados por consulta direta, mas os repositórios privados **não foram copiados nem tiveram conteúdo publicado**.

### Scientific-Research-Engineer (private; 19 candidatos)

| Caminho original | Classificação |
|---|---|
| `docs/PROMPTS_IMPORTACAO_2026-10-15.md` | Orquestração / execução / arquivo histórico |
| `prompts/CONJETRA.md` | Hipóteses / inovação / pré-manuscrito |
| `prompts/LEMA.md` | Derivação / verificação matemática |
| `prompts/MATHMEM_PLUS.md` | Derivação / verificação matemática |
| `prompts/originais/extras/00_PROMPT_MESTRE_ARTIGONOVO_ATR.md` | Orquestração / execução / arquivo histórico |
| `prompts/originais/extras/01_PROMPT_MESTRE_ArtigoNovo.md` | Orquestração / execução / arquivo histórico |
| `prompts/originais/extras/AUDITORIA_TEORIA_MATEMATICA_E_PLAGIO_DETECTOR_DARK.md` | Derivação / verificação matemática |
| `prompts/originais/mestres/BIO-DISCUSSION-RIGOR_v1.0.md` | Pesquisa biológica / discussão |
| `prompts/originais/mestres/CONJETRA_PROMPT_MESTRE.txt` | Hipóteses / inovação / pré-manuscrito |
| `prompts/originais/mestres/MATHMEM_PLUS_MASTER_PROMPT.md` | Derivação / verificação matemática |
| `prompts/originais/mestres/PROMPTS_R90_MULTIAAGENTES.md` | Orquestração / execução / arquivo histórico |
| `prompts/originais/mestres/PROMPT_MESTRE_ARTIGO_TEORICO_DIDATICO_FINAL_DNA_FIRST.md` | Redação / estrutura / preparação editorial |
| `prompts/originais/mestres/PROMPT_MESTRE_RADAR_CIENTIFICO_ASTROFISICA.md` | Revisão bibliográfica / descoberta |
| `prompts/originais/pipeline_18/03_DOMAIN_SCIENTIFIC_AUDIT.md` | Orquestração / execução / arquivo histórico |
| `prompts/originais/pipeline_18/08_DIDATICO_DNA_FIRST.md` | Redação / estrutura / preparação editorial |
| `prompts/originais/pipeline_18/09_NARRATIVA_CONTINUA_SEM_REDUCAO.md` | Redação / estrutura / preparação editorial |
| `prompts/originais/pipeline_18/10_HUMAN_SCIENTIFIC_HSEF2.md` | Redação / estrutura / preparação editorial |
| `prompts/originais/pipeline_18/13_TARGET_JOURNAL_READINESS.md` | Redação / estrutura / preparação editorial |
| `prompts/originais/pipeline_18/14_FIGURES_TABLES_VISUAL_QA.md` | Redação / estrutura / preparação editorial |

### SRE-TRIAD-Scientific-Research-Engine- (private; 1 candidatos)

| Caminho original | Classificação |
|---|---|
| `prompts/PROMPT_MESTRE.md` | Orquestração / execução / arquivo histórico |

### Bio (private; 3 candidatos)

| Caminho original | Classificação |
|---|---|
| `prompts/BIO_ISA_EXECUCAO_AUDIT_MODEL_REPORT_V1.md` | Pesquisa biológica / discussão |
| `prompts/BIO_MASTER.md` | Pesquisa biológica / discussão |
| `prompts/BIO_V02_EXECUTE.md` | Pesquisa biológica / discussão |

### Radar-Plus (private; 33 candidatos)

| Caminho original | Classificação |
|---|---|
| `docs/V552_PROMPT_COMPLETAR_DOSSIER.md` | Orquestração / execução / arquivo histórico |
| `handoff/01_PROMPT_MESTRE_V5_5.md` | Orquestração / execução / arquivo histórico |
| `prompts/agents/EDITOR.md` | Redação / estrutura / preparação editorial |
| `prompts/agents/GATEKEEPER.md` | Auditoria / refutação / anterioridade |
| `prompts/agents/HDE.md` | Hipóteses / inovação / pré-manuscrito |
| `prompts/agents/LEMA.md` | Derivação / verificação matemática |
| `prompts/agents/LITERATURA.md` | Revisão bibliográfica / descoberta |
| `prompts/agents/MATEMATICA.md` | Derivação / verificação matemática |
| `prompts/agents/MFE.md` | Hipóteses / inovação / pré-manuscrito |
| `prompts/agents/NUMERICO.md` | Simulação / validação numérica |
| `prompts/agents/REFUTACAO.md` | Auditoria / refutação / anterioridade |
| `prompts/agents/SDE.md` | Orquestração / execução / arquivo histórico |
| `prompts/discovery/00_GATES_CIENTIFICOS.md` | Auditoria / refutação / anterioridade |
| `prompts/hde/01_HAMILTONIAN_DISCOVERY.md` | Derivação / verificação matemática |
| `prompts/legacy_v552/01_PROMPT_MESTRE_V5_5.md` | Orquestração / execução / arquivo histórico |
| `prompts/legacy_v552/PROTOCOLO_MESTRE_ROPC_V1.md` | Orquestração / execução / arquivo histórico |
| `prompts/legacy_v552/V552_PROMPT_COMPLETAR_DOSSIER.md` | Orquestração / execução / arquivo histórico |
| `prompts/manifest.json` | Orquestração / execução / arquivo histórico |
| `prompts/mfe/01_MULTI_FORMALISM.md` | Derivação / verificação matemática |
| `prompts/phases/00_MESTRE.md` | Orquestração / execução / arquivo histórico |
| `prompts/phases/01_ESCOPO.md` | Revisão bibliográfica / descoberta |
| `prompts/phases/02_BIBLIOGRAFIA.md` | Revisão bibliográfica / descoberta |
| `prompts/phases/03_LEITURA.md` | Revisão bibliográfica / descoberta |
| `prompts/phases/04_ANTERIORIDADE.md` | Auditoria / refutação / anterioridade |
| `prompts/phases/05_HIPOTESES.md` | Hipóteses / inovação / pré-manuscrito |
| `prompts/phases/06_MATEMATICA.md` | Derivação / verificação matemática |
| `prompts/phases/07_SIMULACAO.md` | Simulação / validação numérica |
| `prompts/phases/08_ADVERSARIAL.md` | Orquestração / execução / arquivo histórico |
| `prompts/phases/09_PORTFOLIO.md` | Hipóteses / inovação / pré-manuscrito |
| `prompts/phases/10_PREMANUSCRITO.md` | Hipóteses / inovação / pré-manuscrito |
| `prompts/phases/11_EDITORIAL.md` | Redação / estrutura / preparação editorial |
| `prompts/phases/12_HANDOFF.md` | Orquestração / execução / arquivo histórico |
| `prompts/phases/13_DECISAO.md` | Orquestração / execução / arquivo histórico |

### Supercondutor_HTc (public; 1 candidatos)

| Caminho original | Classificação |
|---|---|
| `prompt_claude_code.md` | Orquestração / execução / arquivo histórico |

### pbh-mb-sim (private; 1 candidatos)

| Caminho original | Classificação |
|---|---|
| `PROMPT_CLAUDE_CODE_simulacao.md` | Simulação / validação numérica |


**Total rastreado nesse escopo:** 58 caminhos candidatos (inclui arquivos auxiliares, manifestos e redundâncias). **Não é total de metodologias únicas.**

## 3. Fontes recuperadas em Drive / Biblioteca

| Documento identificado | Origem / observação |
|---|---|
| `GUIA_18_PROMPTS_PIPELINE_ARTIGOS_CIENTIFICOS_20261004.pdf` | Drive — guia consolidado; múltiplas cópias |
| `PROMPTS_COMPLETOS.md` | Drive — nome encontrado; conteúdo e versões precisam ser conciliados |
| `ALL_PRD_PROMPTS.md` | Drive — coletânea de prompts PRD |
| `PROMPT_MESTRE_ARTIGO_TEORICO_DIDATICO_FINAL_DNA_FIRST.md` | Drive — artigo teórico-didático |
| `HUMAN_SCIENTIFIC_V2_HSEF2.md` | Drive e Biblioteca — protocolo completo disponível |
| `HUMAN_SCIENTIFIC_V3_DNA_PCL_PVP_RP_CUR.md` | Drive — versão por manuscrito |
| `HSEF2_PROTOCOL.md` | Drive |
| `REFERIS_PROTOCOL.md` | Biblioteca ChatGPT — protocolo verificado |
| `REFEREE_V2_PROTOCOL.md` | Biblioteca ChatGPT — protocolo verificado |
| `MATHMEM_PLUS_MASTER_PROMPT.md` | Biblioteca ChatGPT e GitHub privado — protocolo original verificado |
| `PROMPT_MESTRE_AVALIACAO_ARTIGO_P00_P15.md` | Biblioteca ChatGPT |

## 4. Referências históricas que exigem reconciliação

As entradas abaixo constam no histórico de trabalhos, mas **não houve recuperação e comparação integral de seus arquivos canônicos nesta rodada**. Não são apresentadas como cópias dos prompts originais.

| Prompt ou conjunto | Uso registrado | Estado |
|---|---|---|
| PROMPT_MESTRE_AVALIACAO_ARTIGO_P00_P15.md | Auditoria integral P00–P15 | Fonte parcial: Biblioteca ChatGPT |
| PROMPT_MASTER_SEQUENCIAL_ARTIGO_NLQM_2026-10-12.md | Revisão e evidências em artigo NLQM | Fonte parcial: Histórico de projeto |
| MATHMEM_PLUS_NLQM_V1_PROMPTS_AGENTS_2026-10-12.md | Instância NLQM do MATHMEM Plus | Fonte parcial: Histórico de projeto |
| PROMPT 32 — Controlled Figure Replacement | Substituição de figuras, equivalência e gate visual | Fonte parcial: Histórico de projeto |
| PROMPT 37 — Human Scientific Final | Revisão final de manuscrito e suplemento | Fonte parcial: Drive; há relatórios e PDFs de execução |
| P00–P11 TiO₂–PCBM | Auditoria de DRX/DRS, propriedades ópticas, RhB, figuras e consistência | Fonte parcial: Histórico de projeto |
| MASTER PROMPT — Scientific English Reconstruction of the TiO₂ Anatase–Rutile Manuscript | Reconstrução disciplinada em inglês | Fonte parcial: Histórico de projeto |
| DNA_CURCUMA_AUDITORIA_INTEGRAL_V3 | Auditoria documental, analítica e editorial | Fonte parcial: Histórico de projeto |
| AOR–EXO–ARTIGONOVO–WORK V1.0 | Pesquisa exocometas TESS, validação observacional | Fonte parcial: Histórico de projeto |
| Scientific Manuscript Strengthening and Disciplined Rewriting | Auditoria, alinhamento evidência e reescrita disciplinada | Fonte parcial: Histórico de projeto |
| 14 prompts de manuscrito dark-photon | Auditoria, exclusões, modelagem modal e versão final | Fonte parcial: Histórico de projeto |
| Pacote de 6 prompts ITD / SYK | Reprodução, observáveis, ruído e síntese estatística | Fonte parcial: Histórico de projeto |
| M0×M1 TiO₂–PCBM CLAUDE_AGENT | Seleção de modelos e reprodutibilidade | Fonte parcial: Histórico de projeto |
| CLAUDE Code HTC / HTC WORK | Execução de simulações e validação de controles | Fonte parcial: GitHub/Drive |
| Prompt de parceria Renato Grilo–ZnO | Modelo teórico e simulações para colaboração | Fonte parcial: Histórico de projeto |
| Prompt mestre GW150914 ringdown | Aquisição GWOSC e testes adversariais | Fonte parcial: Histórico de projeto |
| PROMPT_MESTRE_ARTIGO_TEORICO_DIDATICO_FINAL_DNA_FIRST.md | Artigo teórico-didático | Fonte parcial: GitHub/Drive |
| PROMPTS_R90_MULTIAAGENTES.md | Auditorias multiagentes e relatórios R90 | Fonte parcial: GitHub |
| PROMPT_MESTRE_RADAR_CIENTIFICO_ASTROFISICA.md | Radar bibliográfico de astrofísica | Fonte parcial: GitHub |
| PROMPT_MESTRE_ARTIGONOVO_ATR.md | Inovação e construção de manuscrito ATR | Fonte parcial: GitHub |

## 5. Critérios de inclusão e governança

1. **CONFIRMADO_GITHUB:** arquivo existente na árvore Git, caminho exato identificado; versão do texto não necessariamente auditada.
2. **CONFIRMADO_BIBLIOTECA_DRIVE:** arquivo encontrado por nome em fonte pessoal; duplicatas e versões ainda em reconciliação.
3. **HISTÓRICO:** nome/procedimento mencionado em projetos anteriores, sem corpo canônico validado.
4. **NOVO:** protocolo escrito especificamente para SMI, nunca confundido com original.
5. **RESTRITO:** manter corpo original na fonte privada até avaliação de direitos, dados científicos inéditos, chaves/credenciais e permissões.

## 6. Ordem preferencial de uso num artigo científico

`RADAR/CONJETRA → LEMA/MATHMEM Plus → DNA-FIRST → HUMAN-SCIENTIFIC → REFERIS/REFEREE v2 → auditoria de figuras/referências → SUBMISSION FREEZE`.

Essa ordem é uma **proposta de integração**, não a ordem normativa de todos os prompts originais. Cada etapa deve admitir `PASS/FAIL/BLOCKED/INCONCLUSIVE` e preservar resultados nulos.

## 7. Limites deste inventário

- Não foi feita varredura de todo o armazenamento local, todas as pastas Drive ou todos os arquivos ZIP embutidos.
- Alguns arquivos no Drive são duplicados; contagens brutas exageram o total de prompts distintos.
- A lista de caminhos GitHub cobre os repositórios acessíveis enumerados acima, **não todo o GitHub, nem pastas não conectadas**.
- Nenhuma cópia integral de fontes privadas foi enviada a este repositório público.

Veja [proveniência](PROVENIENCIA_E_PRIVACIDADE.md).
