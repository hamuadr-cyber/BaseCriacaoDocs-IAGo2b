# Documentos Referência para construção do doc31

**Nome In Natura:** doc31: go2b_lookup.json

**Data de Processamento:** 04/09/2025 15:08:10

**Processo RJ:** 1039604-94.2023.8.26.0405

**Inquérito MPF:** 1.16.000.001860/2025-10

**Cadeia de Custódia:** MANTIDA (Hashes SHA-256 registrados)

**Audit Log:** MEGA_AUDIT_20250904_150743.log

---

## Temática do Documento

O **doc31** trata do tema: **Tabela de lookup e mapeamento de referências**

Os documentos abaixo são utilizados como **referência para extração desta temática específica**, não para uso integral. A referência pode conter múltiplos temas e complexidades, podendo apresentar duplicidades que serão tratadas nas fases posteriores.

## Controles de Segurança e Auditoria

- **Backup de Segurança:** Criado antes do processamento
- **Hashes de Integridade:** Calculados para todos os arquivos
- **Log de Auditoria:** Todas as operações registradas
- **Normalização UTF-8:** Aplicada preservando conteúdo original
- **Classificação LGPD:** Documentos classificados por sensibilidade

---

## Arquivos/Documentos Utilizados como Referência

1. `analysis_go2b_lookup.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `f6b3a1bfeeb4dbc93fe529eeaff6cee4ed114bd237dccc8a7166fa67c9630fa4`
   - Sensibilidade: ALTA_SENSIBILIDADE

2. `analysis_go2b_lookup_20250826_204000.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `57778b32394e7e401d20c5afdde98479dbc33344a2478b64922cab4b5559ffb8`
   - Sensibilidade: ALTA_SENSIBILIDADE

3. `go2b_lookup.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `92e40ec785ac73d5217989d81609452438c0ca3734088a7ebdfdcc6f1244c0a9`
   - Sensibilidade: ALTA_SENSIBILIDADE

4. `reconciliado_go2b_lookup.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `14289805ab497af91173874b1c457a8baf6d2c42f7c027056b11a45fb8b4b1d7`
   - Sensibilidade: ALTA_SENSIBILIDADE

---

\newpage

================================================================================
DOCUMENTO: analysis_go2b_lookup.json
REFERÊNCIA: doc31-referencia
PROCESSADO EM: 04/09/2025 15:08:10
HASH ORIGINAL: f6b3a1bfeeb4dbc93fe529eeaff6cee4ed114bd237dccc8a7166fa67c9630fa4
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 4 chaves
Chaves principais:
  - metadata: dict
  - content_extraction: dict
  - analise_claude: dict
  - contexto_go2b: dict

=== CONTEÚDO JSON ===
metadata:
  file: go2b_lookup.json
  path: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/desenvolvimentos_outros/go2b_lookup.json
  timestamp: 2025-09-01T16:36:10.435986
  size: 25591
  type: json
  descricao: 
  is_critical: False
  preservacao: 100% conteudo mantido
content_extraction:
  success: True
  full_content:
    comunicacoesealertas-faltaatuacaopl-ceo.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
      sha256: f0b272a16c5efdb509f03afc3465dd6ecf24c0c583ce696cc0a04ab7c3e68769
      size: 1358927
    dagobertopadraopl.-diversos.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/DagobertoPadraoPL.-Diversos.pdf
      sha256: 00b42929b0bcabf086f8d4b6ea1071b17e850da60a5b0af9aca73502b1f6be8b
      size: 298291
    contextoehistoricoimp.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ContextoeHistoricoImp.pdf
      sha256: 9d77128c18f635ed6370562c9a60d47da676820885167e61d83071d16d0076db
      size: 1465895
    peticao09062025-1039604-94.2023.8.26.0405.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/Peticao09062025-1039604-94.2023.8.26.0405.pdf
      sha256: 055b175d168ab4869bb772a7a17c62ccdbb4010acae64e9ad7272083d72791b2
      size: 335974
    doccen-historicocontexto.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/DOCCEN-HistoricoContexto.pdf
      sha256: b466ed9f384b0b2c452fb5dbd9cf72293393827d115f329cb0618954c53120c7
      size: 2120767
    contratorecupjudicial.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ContratoRecupJudicial.pdf
      sha256: 336aacba3d456ea9af68134f9620cf58de702415b5da394346f0f34999728beb
      size: 683613
    legal-document-matrix-analysis---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Legal Document Matrix Analysis - Claude.pdf
      sha256: 53714691749d482a8f32eb37e7c53ee58e269cab0f1b8ea39d3dd4dd80ba3b68
      size: 366235
    legal-document-analysis-protocol---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Document Analysis Protocol - Claude.pdf
      sha256: 97bb6eb87509ec7630d6cb584063cfa886346b81ac54aae449e447676beb1ba8
      size: 453360
    github-raw-files-analysis---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/GitHub Raw Files Analysis - Claude.pdf
      sha256: dbdbb765bb194d677e0a05b4ffcc075c0828e0b7b47744de0a836bff67e620fd
      size: 703027
    detalhamentodeconteudodocumentos.txt:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/DetalhamentodeConteudoDocumentos.txt
      sha256: 8c4bb9a3c9a46e8fe1eaa2c445ebcefb21f9183d56bcaf82171ca5cc11f01ee5
      size: 7961
    todosfusao.txt:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.txt
      sha256: 545d0c66c8ac553d86e0d70cfc1796053ff95c38999b94a823ba00abf120d7be
      size: 2638045
    todosfusao.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.pdf
      sha256: bdd86800904c452cd3064be787b165ff128732d840e4031b62907c518b383a81
      size: 26843030
    chatsclaudeprojeto.txt:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaudeprojeto.txt
      sha256: 8770a1d35a71f61174c58492fd2055240cf6ea61142db0ff9ab31f6f5e04e953
      size: 492873
    artefatos.txt:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/artefatos.txt
      sha256: 512384296e4082db815d850455b66db77e7117ca6b3a21b213faeb91cf8daca9
      size: 1106731
    chatsclaudeprojeto.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/chatsclaudeprojeto.pdf
      sha256: ac73565b36e7cc8e195d0a1196dea8ea4ee6724902c959ce1c4ccca4008f7b81
      size: 12177994
    artefatos.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/artefatos.pdf
      sha256: 66bd9ec71221728dbbefa3c914d08d830617e2d33620521104b2258b7d6b6a07
      size: 2543890
    memoriainstitucional.txt:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional.txt
      sha256: 3c436091e8f80e45f8c57b45a783a3d519a8043c2829d5139426bf24ed7e9121
      size: 28974
    judicial-recovery-legal-analysis---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Judicial Recovery Legal Analysis - Claude.pdf
      sha256: d2c11c6b0b8c34452ed4e8d994f95aa3cfbd33ca345d348e108ab49dbca4926e
      size: 464470
    go2b-judicial-recovery-protocol---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Judicial Recovery Protocol - Claude.pdf
      sha256: 9b566fd938836c409055d89c11cb97a6a4fd5a5c7ca6b831b867a8da266aaaed
      size: 208103
    prompt-development-for-project-knowledge---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Prompt Development for Project Knowledge - Claude.pdf
      sha256: c02a90a966f3babb169046d8f76943d79b2a6416ebcc13086a058b82a2860c74
      size: 512866
    projeto-go2b-protocolo-iniciado---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto GO2B Protocolo Iniciado - Claude.pdf
      sha256: 5e2eeaea5a672c779f43b097f9fea7e9140aef9ddd892ce5ff4528f93511c68a
      size: 354394
    go2b-protocol-initialization---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Protocol Initialization - Claude.pdf
      sha256: fce053a4524871fd5730bcac5362e3d9ede05eef65d0e7b05475957ba63d7760
      size: 409906
    judicial-recovery-process-strategy---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Judicial Recovery Process Strategy - Claude.pdf
      sha256: 1b70542e6ef5083069728ceeff8a11c3a70f9a44552fc628fea84a1bb46bad8a
      size: 213837
    projeto-go2b-protocol-initialization---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto GO2B Protocol Initialization - Claude.pdf
      sha256: 6ed1158f04ca3d8c1ebe665b52de7fc2fa832f6950ecc2e6a362994f89c23d5c
      size: 241172
    go2b-project-protocol-initialization---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Go2B Project Protocol Initialization - Claude.pdf
      sha256: bd63849870a9f42e65b8024b0b9f8b060089c8e95f20f1fe5028997035abc7d7
      size: 295372
    go2b-legal-protocol-initialization---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Legal Protocol Initialization - Claude.pdf
      sha256: 4cc02e4dc63a5a5d6a9ec99171e0f772834190b464fe933d3abd47f036b3db81
      size: 467772
    go2b-institutional-memory-protocol---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Institutional Memory Protocol - Claude.pdf
      sha256: 25bb07d06621d2cab3605c2c9283f0523395091a9349b271e2eb7073cef4e158
      size: 213797
    legal-research-project-go2b---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Research Project GO2B - Claude.pdf
      sha256: 0b4c3824bacbceded1481f69a3e3351dfb713f3d95c05cb3b14fb05a408f9d0a
      size: 337729
    legal-investigation-strategy-framework---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Investigation Strategy Framework - Claude.pdf
      sha256: 6bf94448dfd44dc23bc1ff3e6ef79117bacac0182eec6f5d84b24fa5065c5e6b
      size: 276679
    legal-documentation-compliance-strategy---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Documentation Compliance Strategy - Claude.pdf
      sha256: ba622f7e45496774fa1a80e8f04be1501031a34d75503d3d41d5a1ddd4128bbb
      size: 212142
    go2b-judicial-recovery-analysis---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Judicial Recovery Analysis - Claude.pdf
      sha256: 172354d82159bf1a20898ff57ef93b416a715fde4c41ea4f9e89470c0b18e3a2
      size: 890934
    projeto-knowledge-document-review---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto Knowledge Document Review - Claude.pdf
      sha256: 1f801a952593ebae43efb1bb1dd40cf333d51fc908714925c52c070df85998f6
      size: 3754159
    legal-document-integration-project---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Document Integration Project - Claude.pdf
      sha256: e52e6e00ca23cc224f2f60db12fcadedc87921ded378d301ad924bb39f943cb5
      size: 155923
    ect-correios-legal-processes-analysis---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/ECT-Correios Legal Processes Analysis - Claude.pdf
      sha256: 51eae5fa6f6aea7343b8768073eb3327490e7674690038684143c6064b744c3f
      size: 261352
    relatorio-de-consolidacao-de-fases---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Relatório de Consolidação de Fases - Claude.pdf
      sha256: e38b7628456e50c8a636d0044f38d61818dfa258f2a0bff7027de2a034467af3
      size: 170156
    judicial-administrator-investigation---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Judicial Administrator Investigation - Claude.pdf
      sha256: 33af2ad5a10bb5360afab0da610ce92da0929bba195f1d2e892c97c2725e8bc0
      size: 359527
    legal-case-go2b-strategic-analysis---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Case GO2B Strategic Analysis - Claude.pdf
      sha256: fcfe0616295b7e554f65a81f9e39e7f2620dfbf4e14595bf4c611f566e07c8f5
      size: 259562
    legal-documentation-consolidation-project---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Documentation Consolidation Project - Claude.pdf
      sha256: c5793551a7504f16eb930705150d9ad083573717671a32ee74e226f74fd42c26
      size: 377991
    go2b-case-document-consolidation---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Case Document Consolidation - Claude.pdf
      sha256: 760802bd3c27dead69ec729aaaae60cb436e164e0a129e0b7782b568e1f41773
      size: 294352
    go2b-business-crisis-strategy---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Business Crisis Strategy - Claude.pdf
      sha256: 4b5b30e969d180c2f3d5852f11829ac469d75b1b235f36611b68f95a3957ba16
      size: 330029
    go2b-investigative-analysis---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Investigative Analysis - Claude.pdf
      sha256: 2612b46c85726364a95edf60f289bb29fb5cb9cba5e818cf4eaaef0b64d4a1c7
      size: 264395
    digital-knowledge-matrix-construction---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Digital Knowledge Matrix Construction - Claude.pdf
      sha256: 76d9cea91725e1f1cb91395797a0a974b08849dd99e59c235070b139ad34a2fc
      size: 368308
    project-knowledge-matrix-json---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Project Knowledge Matrix JSON - Claude.pdf
      sha256: 965eb9e324e9ea004ce103dad9baf827359c1a5faae07d481a969e5de71d8e7a
      size: 607128
    go2b-project-knowledge-matrix---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Project Knowledge Matrix - Claude.pdf
      sha256: dab88f249a21cfe0e1ffec0fc51aa83a62c9a5be365afa2a746a7f70c024f290
      size: 555436
    json-matrix-project-knowledge-analysis---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/JSON Matrix Project Knowledge Analysis - Claude.pdf
      sha256: daed196f9f69896e6897ac8b6b7158388307e8ee21ac44c5e952a539547d56ae
      size: 358332
    matrix-integration-and-knowledge-maximization---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Matrix Integration and Knowledge Maximization - Claude.pdf
      sha256: 209d5ffe6e9f5cc851e29645c7b9884b0365dc05a44d92cf2a475b2a470843fb
      size: 607073
    json-matrix-protocol-development---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/JSON Matrix Protocol Development - Claude.pdf
      sha256: 2017772c2a24b4fdc9478f926283c52c24f645681070ef19d5c9b10b183dd903
      size: 279607
    documentosbaseconhecimento.txt:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosbaseconhecimento.txt
      sha256: 539771468b44f8cc30d002897df7b502ee950699e99e54ca37731fcfe98ec3e9
      size: 712175
    documentosbaseconhecimento.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/documentosbaseconhecimento.pdf
      sha256: 54118726f5790f80a5515c41add7834e2b1257a261434c30ab8f9a62dc6417d4
      size: 12150092
    memoriainstitucional.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/memoriainstitucional.pdf
      sha256: 18dc2697ee4e02df50c516f6bdbc841e75a25e9beb8912f526d801e17e3ad486
      size: 95214
    go2b-institucionalgpt.txt---bloco-de-notas.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/Go2b-InstitucionalGPT.txt - Bloco de notas.pdf
      sha256: a463c863f6006f6df095b80c536fe6830b01485a9e305a1bfcbe367434760389
      size: 38699
    go2b_memoria_institucional.md---bloco-de-notas.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/go2b_memoria_institucional.md - Bloco de notas.pdf
      sha256: 9f68e40bcc6290bfdf2b6d1053c67033d7a515e4bdc13df8d629680a4dc55078
      size: 59149
    recupjudicial-analiseinicialfinancont.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RecupJudicial-AnaliseInicialFinanCont.pdf
      sha256: a677c679187c7724f3d9ca3cddb2871d4ffdd67c45b8ae9b706930ce7a867cf4
      size: 243606
    go2b-institucionalgpt.txt:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/Go2b-InstitucionalGPT.txt
      sha256: da24dbc1c182c1018e9b6bac8675684134ec35acc7a14a0d182f9f12c568bcba
      size: 10541
    go2b_memoria_institucional.md:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/go2b_memoria_institucional.md
      sha256: d6f959be0553156a85d3cc1684ad786abdd96830bc7e43f7a145087f326974ef
      size: 19797
    relatorio_rj_go2b.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/relatorio_rj_go2b.pdf
      sha256: df8d4a37ff9e248e7546fad290e16db42584e760be37092176c884734238829b
      size: 33169
    relatorio_fases_complemento_dossie-mafia-judicial-go2b.md---bloco-de-notas.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/relatorio_fases_complemento_dossie-mafia-judicial-go2b.md - Bloco de notas.pdf
      sha256: e6d3a43b3b773880afd86630d52f47ca8fd63662b1005249891b39dfa1fa0fc2
      size: 60689
    relatorio_fases_1_2_3_4_consolidadocompletotemas.md---bloco-de-notas.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/relatorio_fases_1_2_3_4_consolidadoCompletoTemas.md - Bloco de notas.pdf
      sha256: fb281949a19348628c460423a1efb4661d630669a09c75fd084704f18e497803
      size: 244476
    fusaointegradago2brecupjudicialgptcomenviodocsvs02.md---bloco-de-notas.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
      sha256: 30c3db760ca2d0d412438669aecf03d6764faebeb9cb48bc71968b1645252424
      size: 742967
    fusaointegradago2brecupjudicialgptcomenviodocsvs01.md---bloco-de-notas.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
      sha256: a4705c43de3ee368172575ac27d9b19a02591ec556262646d7f169586cbde3e4
      size: 476982
    fusaoartefatos_a_b_c_incompletovsclaude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaoartefatos_a_b_c_Incompletovsclaude.pdf
      sha256: e9b1f08f9a7db8a63fad3e3bd0654bb69f6b7734e1013d0521498fbb1c65a183
      size: 222449
    legal-defense-strategy-documentation---claude.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/Legal Defense Strategy Documentation - Claude.pdf
      sha256: f6c63b0a693c03d055f5c140f9e04339b14ed6554db06bb0a04e0c371dae8625
      size: 429183
    go2b_fusaogpt25082025.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/GO2B_FusaoGPT25082025.pdf
      sha256: 7a549f983e598f89d750987760eeba05a3dfeb7ebb491788cd4b7b13974e2fb9
      size: 477088
    mpf-juntadaautosect-completo-vs25082025.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/MPF-JuntadaAutosECT-Completo-vs25082025.pdf
      sha256: 6d06824add65dd5fe5a51f6aab6ade27816ffed98d74d56acbb93e4432469eec
      size: 3269735
    posicionamentopl-questionamentosjul2024.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/PosicionamentoPL-QuestionamentosJul2024.pdf
      sha256: d8b702bb94bb4282598eca60d283d4e90e4f969c61fd4a7a67fa5bdc9defbdc4
      size: 213672
    posicionamentopl-questionamentosago2024.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/PosicionamentoPL-QuestionamentosAgo2024.pdf
      sha256: fa7b15a90aeb59baa33564cce2a2580750e372894e316d215cace510f40afedb
      size: 117091
    posicionamentopl-questionamentosset2024.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/PosicionamentoPL-QuestionamentosSet2024.pdf
      sha256: 75192d0479c68f78ed33729b0dfe32b9f3857a3835de6e618c644d3b58ae7070
      size: 121890
    posicionamentopl-suspensaoquestionados.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/PosicionamentoPL-SuspensaoQuestionados.pdf
      sha256: e875ddb52b31aff72ba83dc9f0a4313f76b4689c1c8f5e0b8525fe07578ad6e0
      size: 117091
    relatoriotrocadns19052025.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RelatorioTrocaDNS19052025.pdf
      sha256: ed05946c7324112e61528c6b8f7af9cfe982f77bb89b0eb63838fe8bed904a6b
      size: 1045522
    estrategiasepilaresjun25consol.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/EstrategiasePilaresJun25Consol.pdf
      sha256: eb9392862f0de388861a43f603315bb2e068e2be93cfa6e060a42b53d604a52c
      size: 1519397
    padraoatuacaopl-dagoberto-exemplo.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/PadraoAtuacaoPL-Dagoberto-Exemplo.pdf
      sha256: 29b243777d9a4f13d0ff35f9678b2d1092083f32a9b01c707c4bdac6cd41fa2a
      size: 423160
    processoqueresultouapropriacaocredito-dirceu.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ProcessoqueResultouApropriacaoCredito-Dirceu.pdf
      sha256: d129b26fa37289b15c946f0b47f267ba86f49dc606b10264b1ac06ad8b3ae628
      size: 232648
    processoqueresultouapropriacaocredito-dagoberto.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ProcessoqueResultouApropriacaoCredito-Dagoberto.pdf
      sha256: 14430cc2e8415b6b46a79cf9b314dc1556adc696f97ad486cecbac95e65c75e9
      size: 129298
    dez2023negociacaoinicialctorj.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/Dez2023NegociacaoInicialCtoRJ.pdf
      sha256: df8ecb5e473facec4bab61d06f405279c5df602b9616d358e5b6775a0c600c0f
      size: 83036
    comunicacoesealertas-faltaatuacaopl-jur.pdf:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseAlertas-FaltaAtuaçaoPL-Jur.pdf
      sha256: 8498f85865f92576ac0fc39456cf89bfa060aeb35d6abc38643634410160f3cf
      size: 526415
    analise_rj_completa.json:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/MatrizJson/analise_rj_completa.json
      sha256: 54402bff4639b6f0e278f53ca3258eff838aecef7e8315396729c7c9c6098a7d
      size: 50439
    matriz_unificada_go2b_v7.json:
      path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/MatrizJson/matriz_unificada_go2b_v7.json
      sha256: 8b8e7aa7cdf19a9ab18a6208bb857e8f53540da66d745814ba1cbc8d6710477e
      size: 189172
  preview: {'comunicacoesealertas-faltaatuacaopl-ceo.pdf': {'path': '/Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseA... [TRUNCADO]
  error: None
analise_claude:
  analise_ia_completa:
    resumo_documento: Arquivo de lookup contendo mapeamento detalhado de documentos relacionados ao caso GO2B vs PL/ECT, incluindo relatórios, análises, petições e documentos institucionais. Estrutura organizada com paths,... [TRUNCADO]
    contexto_caso: Este documento serve como índice mestre e catálogo de evidências documentais do caso, permitindo rastreabilidade e autenticidade dos documentos através de hashes criptográficos
    informacoes_chave:
      [0]:
        Existência de múltiplos relatórios de análise jurídica e estratégica
      [1]:
        Documentação sobre troca irregular de DNS em 19/05/2025
      [2]:
        Evidências de questionamentos à PL entre Jul-Set 2024
      [3]:
        Relatórios sobre padrões de atuação suspeitos de Dagoberto e Dirceu
      [4]:
        Documentos sobre apropriação de créditos
      [5]:
        Análises da recuperação judicial e estratégias de defesa
      [6]:
        Matrizes de conhecimento unificadas em formato JSON
    relevancia_juridica: alta - documento fundamental para garantir cadeia de custódia e integridade das evidências através dos hashes SHA256, além de mapear todo o acervo probatório do caso
    recomendacoes:
      [0]:
        Manter backup criptografado deste catálogo
      [1]:
        Verificar regularmente integridade dos hashes
      [2]:
        Criar índice cruzado por temas/assuntos
      [3]:
        Estabelecer protocolo de atualização do catálogo
      [4]:
        Priorizar análise dos documentos sobre apropriação de créditos
  irregularidades:
    apropriacao_cmz:
      detectada: True
      evidencias:
        [0]:
          ProcessoqueResultouApropriacaoCredito-Dirceu.pdf
        [1]:
          ProcessoqueResultouApropriacaoCredito-Dagoberto.pdf
      valores:

      responsaveis:
        [0]:
          Dirceu
        [1]:
          Dagoberto
    renuncia_irregular:
      detectada: True
      evidencias:
        [0]:
          RelatorioTrocaDNS19052025.pdf
      timeline:
        [0]:
          19/05/2025 - Troca irregular de DNS
    impedimento_judicial:
      detectada: True
      evidencias:
        [0]:
          PadraoAtuacaoPL-Dagoberto-Exemplo.pdf
      cadeia_interesse:
        [0]:
          PL
        [1]:
          Dagoberto
    negligencia_profissional:
      detectada: True
      padroes:
        [0]:
          Falta de atuação PL
      exemplos:
        [0]:
          ComunicacoeseAlertas-FaltaAtuacaoPL-Jur.pdf
        [1]:
          ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
    custas_cartas:
      detectada: True
      proposta_go2b: Documentada em Dez2023NegociacaoInicialCtoRJ.pdf
      recusa: Evidenciada em questionamentos posteriores
  evidencias_documentais:
    [0]:
      MPF-JuntadaAutosECT-Completo-vs25082025.pdf
    [1]:
      RelatorioTrocaDNS19052025.pdf
    [2]:
      ProcessoqueResultouApropriacaoCredito-Dirceu.pdf
    [3]:
      ProcessoqueResultouApropriacaoCredito-Dagoberto.pdf
  valores_financeiros:

  datas_relevantes:
    [0]:
      19/05/2025 - Troca DNS
    [1]:
      25/08/2025 - Juntada MPF
    [2]:
      09/06/2025 - Petição
    [3]:
      Dez/2023 - Negociação inicial
  pessoas_mencionadas:
    [0]:
      Dagoberto
    [1]:
      Dirceu
    [2]:
      Adriano Hamu
  violacoes_legais:
    [0]:
      Apropriação indevida de créditos
    [1]:
      Renúncia irregular de representação
    [2]:
      Negligência profissional
    [3]:
      Impedimento judicial não declarado
  nexo_causal:
    elementos:
      [0]:
        Troca DNS
      [1]:
        Falta de atuação PL
      [2]:
        Apropriação de créditos
      [3]:
        Padrão suspeito de conduta
    conexoes:
      [0]:
        Troca DNS levou à perda de representação
      [1]:
        Falta de atuação permitiu apropriação
      [2]:
        Padrão de conduta evidencia premeditação
contexto_go2b:
  processo_rj: 1039604-94.2023.8.26.0405
  inquerito_mpf: 1.16.000.001860/2025-10
  status: GO2B SEM REPRESENTACAO DESDE 19/05/2025
  atores_corretos:
    GO2B: VITIMA da apropriacao R$ 600.000
    PL_Consultoria: APROPRIADORA - reteve valores por 120 dias
    CMZ_Creme_Mel: Ex-cliente que PAGOU acordo em 15/12/2023
    Dagoberto: CEO PL - responsavel apropriacao
    Dirceu: Advogado PL - emails superficiais sobre CMZ
    Quintino: Administrador Judicial - coordenacao suspeita
    Adriano_Hamu: CEO GO2B - vitima sem representacao
  valores_criticos:
    apropriacao_cmz: 600000.0
    divida_ect: 387055636.47
    custas_cartas: 18000.0
    impedimento_interesse: 17000000.0
  irregularidades_confirmadas: 5
  chunks_obrigatorios: 758
  confidence_minimo: 0.85

================================================================================
FIM DOCUMENTO: analysis_go2b_lookup.json
REFERÊNCIA: doc31-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: analysis_go2b_lookup_20250826_204000.json
REFERÊNCIA: doc31-referencia
PROCESSADO EM: 04/09/2025 15:08:10
HASH ORIGINAL: 57778b32394e7e401d20c5afdde98479dbc33344a2478b64922cab4b5559ffb8
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 5 chaves
Chaves principais:
  - tipo: str
  - arquivo: str
  - descricao: str
  - estrutura: dict
  - estatisticas: dict

=== CONTEÚDO JSON ===
tipo: json
arquivo: go2b_lookup.json
descricao: Lookup table
estrutura:
  comunicacoesealertas-faltaatuacaopl-ceo.pdf:
    path: str
    sha256: str
    size: int
  dagobertopadraopl.-diversos.pdf:
    path: str
    sha256: str
    size: int
  contextoehistoricoimp.pdf:
    path: str
    sha256: str
    size: int
  peticao09062025-1039604-94.2023.8.26.0405.pdf:
    path: str
    sha256: str
    size: int
  doccen-historicocontexto.pdf:
    path: str
    sha256: str
    size: int
  contratorecupjudicial.pdf:
    path: str
    sha256: str
    size: int
  legal-document-matrix-analysis---claude.pdf:
    path: str
    sha256: str
    size: int
  legal-document-analysis-protocol---claude.pdf:
    path: str
    sha256: str
    size: int
  github-raw-files-analysis---claude.pdf:
    path: str
    sha256: str
    size: int
  detalhamentodeconteudodocumentos.txt:
    path: str
    sha256: str
    size: int
estatisticas:
  tamanho: 24835
  chaves_principais:
    [0]:
      comunicacoesealertas-faltaatuacaopl-ceo.pdf
    [1]:
      dagobertopadraopl.-diversos.pdf
    [2]:
      contextoehistoricoimp.pdf
    [3]:
      peticao09062025-1039604-94.2023.8.26.0405.pdf
    [4]:
      doccen-historicocontexto.pdf
    [5]:
      contratorecupjudicial.pdf
    [6]:
      legal-document-matrix-analysis---claude.pdf
    [7]:
      legal-document-analysis-protocol---claude.pdf
    [8]:
      github-raw-files-analysis---claude.pdf
    [9]:
      detalhamentodeconteudodocumentos.txt
  profundidade: 2

================================================================================
FIM DOCUMENTO: analysis_go2b_lookup_20250826_204000.json
REFERÊNCIA: doc31-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: go2b_lookup.json
REFERÊNCIA: doc31-referencia
PROCESSADO EM: 04/09/2025 15:08:10
HASH ORIGINAL: 92e40ec785ac73d5217989d81609452438c0ca3734088a7ebdfdcc6f1244c0a9
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 77 chaves
Chaves principais:
  - comunicacoesealertas-faltaatuacaopl-ceo.pdf: dict
  - dagobertopadraopl.-diversos.pdf: dict
  - contextoehistoricoimp.pdf: dict
  - peticao09062025-1039604-94.2023.8.26.0405.pdf: dict
  - doccen-historicocontexto.pdf: dict
  - contratorecupjudicial.pdf: dict
  - legal-document-matrix-analysis---claude.pdf: dict
  - legal-document-analysis-protocol---claude.pdf: dict
  - github-raw-files-analysis---claude.pdf: dict
  - detalhamentodeconteudodocumentos.txt: dict

=== CONTEÚDO JSON ===
comunicacoesealertas-faltaatuacaopl-ceo.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
  sha256: f0b272a16c5efdb509f03afc3465dd6ecf24c0c583ce696cc0a04ab7c3e68769
  size: 1358927
dagobertopadraopl.-diversos.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/DagobertoPadraoPL.-Diversos.pdf
  sha256: 00b42929b0bcabf086f8d4b6ea1071b17e850da60a5b0af9aca73502b1f6be8b
  size: 298291
contextoehistoricoimp.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ContextoeHistoricoImp.pdf
  sha256: 9d77128c18f635ed6370562c9a60d47da676820885167e61d83071d16d0076db
  size: 1465895
peticao09062025-1039604-94.2023.8.26.0405.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/Peticao09062025-1039604-94.2023.8.26.0405.pdf
  sha256: 055b175d168ab4869bb772a7a17c62ccdbb4010acae64e9ad7272083d72791b2
  size: 335974
doccen-historicocontexto.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/DOCCEN-HistoricoContexto.pdf
  sha256: b466ed9f384b0b2c452fb5dbd9cf72293393827d115f329cb0618954c53120c7
  size: 2120767
contratorecupjudicial.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ContratoRecupJudicial.pdf
  sha256: 336aacba3d456ea9af68134f9620cf58de702415b5da394346f0f34999728beb
  size: 683613
legal-document-matrix-analysis---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Legal Document Matrix Analysis - Claude.pdf
  sha256: 53714691749d482a8f32eb37e7c53ee58e269cab0f1b8ea39d3dd4dd80ba3b68
  size: 366235
legal-document-analysis-protocol---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Document Analysis Protocol - Claude.pdf
  sha256: 97bb6eb87509ec7630d6cb584063cfa886346b81ac54aae449e447676beb1ba8
  size: 453360
github-raw-files-analysis---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/GitHub Raw Files Analysis - Claude.pdf
  sha256: dbdbb765bb194d677e0a05b4ffcc075c0828e0b7b47744de0a836bff67e620fd
  size: 703027
detalhamentodeconteudodocumentos.txt:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/DetalhamentodeConteudoDocumentos.txt
  sha256: 8c4bb9a3c9a46e8fe1eaa2c445ebcefb21f9183d56bcaf82171ca5cc11f01ee5
  size: 7961
todosfusao.txt:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.txt
  sha256: 545d0c66c8ac553d86e0d70cfc1796053ff95c38999b94a823ba00abf120d7be
  size: 2638045
todosfusao.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.pdf
  sha256: bdd86800904c452cd3064be787b165ff128732d840e4031b62907c518b383a81
  size: 26843030
chatsclaudeprojeto.txt:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaudeprojeto.txt
  sha256: 8770a1d35a71f61174c58492fd2055240cf6ea61142db0ff9ab31f6f5e04e953
  size: 492873
artefatos.txt:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/artefatos.txt
  sha256: 512384296e4082db815d850455b66db77e7117ca6b3a21b213faeb91cf8daca9
  size: 1106731
chatsclaudeprojeto.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/chatsclaudeprojeto.pdf
  sha256: ac73565b36e7cc8e195d0a1196dea8ea4ee6724902c959ce1c4ccca4008f7b81
  size: 12177994
artefatos.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/artefatos.pdf
  sha256: 66bd9ec71221728dbbefa3c914d08d830617e2d33620521104b2258b7d6b6a07
  size: 2543890
memoriainstitucional.txt:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional.txt
  sha256: 3c436091e8f80e45f8c57b45a783a3d519a8043c2829d5139426bf24ed7e9121
  size: 28974
judicial-recovery-legal-analysis---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Judicial Recovery Legal Analysis - Claude.pdf
  sha256: d2c11c6b0b8c34452ed4e8d994f95aa3cfbd33ca345d348e108ab49dbca4926e
  size: 464470
go2b-judicial-recovery-protocol---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Judicial Recovery Protocol - Claude.pdf
  sha256: 9b566fd938836c409055d89c11cb97a6a4fd5a5c7ca6b831b867a8da266aaaed
  size: 208103
prompt-development-for-project-knowledge---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Prompt Development for Project Knowledge - Claude.pdf
  sha256: c02a90a966f3babb169046d8f76943d79b2a6416ebcc13086a058b82a2860c74
  size: 512866
projeto-go2b-protocolo-iniciado---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto GO2B Protocolo Iniciado - Claude.pdf
  sha256: 5e2eeaea5a672c779f43b097f9fea7e9140aef9ddd892ce5ff4528f93511c68a
  size: 354394
go2b-protocol-initialization---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Protocol Initialization - Claude.pdf
  sha256: fce053a4524871fd5730bcac5362e3d9ede05eef65d0e7b05475957ba63d7760
  size: 409906
judicial-recovery-process-strategy---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Judicial Recovery Process Strategy - Claude.pdf
  sha256: 1b70542e6ef5083069728ceeff8a11c3a70f9a44552fc628fea84a1bb46bad8a
  size: 213837
projeto-go2b-protocol-initialization---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto GO2B Protocol Initialization - Claude.pdf
  sha256: 6ed1158f04ca3d8c1ebe665b52de7fc2fa832f6950ecc2e6a362994f89c23d5c
  size: 241172
go2b-project-protocol-initialization---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Go2B Project Protocol Initialization - Claude.pdf
  sha256: bd63849870a9f42e65b8024b0b9f8b060089c8e95f20f1fe5028997035abc7d7
  size: 295372
go2b-legal-protocol-initialization---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Legal Protocol Initialization - Claude.pdf
  sha256: 4cc02e4dc63a5a5d6a9ec99171e0f772834190b464fe933d3abd47f036b3db81
  size: 467772
go2b-institutional-memory-protocol---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Institutional Memory Protocol - Claude.pdf
  sha256: 25bb07d06621d2cab3605c2c9283f0523395091a9349b271e2eb7073cef4e158
  size: 213797
legal-research-project-go2b---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Research Project GO2B - Claude.pdf
  sha256: 0b4c3824bacbceded1481f69a3e3351dfb713f3d95c05cb3b14fb05a408f9d0a
  size: 337729
legal-investigation-strategy-framework---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Investigation Strategy Framework - Claude.pdf
  sha256: 6bf94448dfd44dc23bc1ff3e6ef79117bacac0182eec6f5d84b24fa5065c5e6b
  size: 276679
legal-documentation-compliance-strategy---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Documentation Compliance Strategy - Claude.pdf
  sha256: ba622f7e45496774fa1a80e8f04be1501031a34d75503d3d41d5a1ddd4128bbb
  size: 212142
go2b-judicial-recovery-analysis---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Judicial Recovery Analysis - Claude.pdf
  sha256: 172354d82159bf1a20898ff57ef93b416a715fde4c41ea4f9e89470c0b18e3a2
  size: 890934
projeto-knowledge-document-review---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto Knowledge Document Review - Claude.pdf
  sha256: 1f801a952593ebae43efb1bb1dd40cf333d51fc908714925c52c070df85998f6
  size: 3754159
legal-document-integration-project---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Document Integration Project - Claude.pdf
  sha256: e52e6e00ca23cc224f2f60db12fcadedc87921ded378d301ad924bb39f943cb5
  size: 155923
ect-correios-legal-processes-analysis---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/ECT-Correios Legal Processes Analysis - Claude.pdf
  sha256: 51eae5fa6f6aea7343b8768073eb3327490e7674690038684143c6064b744c3f
  size: 261352
relatorio-de-consolidacao-de-fases---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Relatório de Consolidação de Fases - Claude.pdf
  sha256: e38b7628456e50c8a636d0044f38d61818dfa258f2a0bff7027de2a034467af3
  size: 170156
judicial-administrator-investigation---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Judicial Administrator Investigation - Claude.pdf
  sha256: 33af2ad5a10bb5360afab0da610ce92da0929bba195f1d2e892c97c2725e8bc0
  size: 359527
legal-case-go2b-strategic-analysis---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Case GO2B Strategic Analysis - Claude.pdf
  sha256: fcfe0616295b7e554f65a81f9e39e7f2620dfbf4e14595bf4c611f566e07c8f5
  size: 259562
legal-documentation-consolidation-project---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Legal Documentation Consolidation Project - Claude.pdf
  sha256: c5793551a7504f16eb930705150d9ad083573717671a32ee74e226f74fd42c26
  size: 377991
go2b-case-document-consolidation---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Case Document Consolidation - Claude.pdf
  sha256: 760802bd3c27dead69ec729aaaae60cb436e164e0a129e0b7782b568e1f41773
  size: 294352
go2b-business-crisis-strategy---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Business Crisis Strategy - Claude.pdf
  sha256: 4b5b30e969d180c2f3d5852f11829ac469d75b1b235f36611b68f95a3957ba16
  size: 330029
go2b-investigative-analysis---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Investigative Analysis - Claude.pdf
  sha256: 2612b46c85726364a95edf60f289bb29fb5cb9cba5e818cf4eaaef0b64d4a1c7
  size: 264395
digital-knowledge-matrix-construction---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Digital Knowledge Matrix Construction - Claude.pdf
  sha256: 76d9cea91725e1f1cb91395797a0a974b08849dd99e59c235070b139ad34a2fc
  size: 368308
project-knowledge-matrix-json---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Project Knowledge Matrix JSON - Claude.pdf
  sha256: 965eb9e324e9ea004ce103dad9baf827359c1a5faae07d481a969e5de71d8e7a
  size: 607128
go2b-project-knowledge-matrix---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/GO2B Project Knowledge Matrix - Claude.pdf
  sha256: dab88f249a21cfe0e1ffec0fc51aa83a62c9a5be365afa2a746a7f70c024f290
  size: 555436
json-matrix-project-knowledge-analysis---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/JSON Matrix Project Knowledge Analysis - Claude.pdf
  sha256: daed196f9f69896e6897ac8b6b7158388307e8ee21ac44c5e952a539547d56ae
  size: 358332
matrix-integration-and-knowledge-maximization---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Matrix Integration and Knowledge Maximization - Claude.pdf
  sha256: 209d5ffe6e9f5cc851e29645c7b9884b0365dc05a44d92cf2a475b2a470843fb
  size: 607073
json-matrix-protocol-development---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/JSON Matrix Protocol Development - Claude.pdf
  sha256: 2017772c2a24b4fdc9478f926283c52c24f645681070ef19d5c9b10b183dd903
  size: 279607
documentosbaseconhecimento.txt:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosbaseconhecimento.txt
  sha256: 539771468b44f8cc30d002897df7b502ee950699e99e54ca37731fcfe98ec3e9
  size: 712175
documentosbaseconhecimento.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/documentosbaseconhecimento.pdf
  sha256: 54118726f5790f80a5515c41add7834e2b1257a261434c30ab8f9a62dc6417d4
  size: 12150092
memoriainstitucional.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/memoriainstitucional.pdf
  sha256: 18dc2697ee4e02df50c516f6bdbc841e75a25e9beb8912f526d801e17e3ad486
  size: 95214
go2b-institucionalgpt.txt---bloco-de-notas.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/Go2b-InstitucionalGPT.txt - Bloco de notas.pdf
  sha256: a463c863f6006f6df095b80c536fe6830b01485a9e305a1bfcbe367434760389
  size: 38699
go2b_memoria_institucional.md---bloco-de-notas.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/go2b_memoria_institucional.md - Bloco de notas.pdf
  sha256: 9f68e40bcc6290bfdf2b6d1053c67033d7a515e4bdc13df8d629680a4dc55078
  size: 59149
recupjudicial-analiseinicialfinancont.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RecupJudicial-AnaliseInicialFinanCont.pdf
  sha256: a677c679187c7724f3d9ca3cddb2871d4ffdd67c45b8ae9b706930ce7a867cf4
  size: 243606
go2b-institucionalgpt.txt:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/Go2b-InstitucionalGPT.txt
  sha256: da24dbc1c182c1018e9b6bac8675684134ec35acc7a14a0d182f9f12c568bcba
  size: 10541
go2b_memoria_institucional.md:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/go2b_memoria_institucional.md
  sha256: d6f959be0553156a85d3cc1684ad786abdd96830bc7e43f7a145087f326974ef
  size: 19797
relatorio_rj_go2b.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/relatorio_rj_go2b.pdf
  sha256: df8d4a37ff9e248e7546fad290e16db42584e760be37092176c884734238829b
  size: 33169
relatorio_fases_complemento_dossie-mafia-judicial-go2b.md---bloco-de-notas.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/relatorio_fases_complemento_dossie-mafia-judicial-go2b.md - Bloco de notas.pdf
  sha256: e6d3a43b3b773880afd86630d52f47ca8fd63662b1005249891b39dfa1fa0fc2
  size: 60689
relatorio_fases_1_2_3_4_consolidadocompletotemas.md---bloco-de-notas.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/relatorio_fases_1_2_3_4_consolidadoCompletoTemas.md - Bloco de notas.pdf
  sha256: fb281949a19348628c460423a1efb4661d630669a09c75fd084704f18e497803
  size: 244476
fusaointegradago2brecupjudicialgptcomenviodocsvs02.md---bloco-de-notas.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
  sha256: 30c3db760ca2d0d412438669aecf03d6764faebeb9cb48bc71968b1645252424
  size: 742967
fusaointegradago2brecupjudicialgptcomenviodocsvs01.md---bloco-de-notas.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
  sha256: a4705c43de3ee368172575ac27d9b19a02591ec556262646d7f169586cbde3e4
  size: 476982
fusaoartefatos_a_b_c_incompletovsclaude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaoartefatos_a_b_c_Incompletovsclaude.pdf
  sha256: e9b1f08f9a7db8a63fad3e3bd0654bb69f6b7734e1013d0521498fbb1c65a183
  size: 222449
legal-defense-strategy-documentation---claude.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/Legal Defense Strategy Documentation - Claude.pdf
  sha256: f6c63b0a693c03d055f5c140f9e04339b14ed6554db06bb0a04e0c371dae8625
  size: 429183
go2b_fusaogpt25082025.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/GO2B_FusaoGPT25082025.pdf
  sha256: 7a549f983e598f89d750987760eeba05a3dfeb7ebb491788cd4b7b13974e2fb9
  size: 477088
mpf-juntadaautosect-completo-vs25082025.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/MPF-JuntadaAutosECT-Completo-vs25082025.pdf
  sha256: 6d06824add65dd5fe5a51f6aab6ade27816ffed98d74d56acbb93e4432469eec
  size: 3269735
posicionamentopl-questionamentosjul2024.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/PosicionamentoPL-QuestionamentosJul2024.pdf
  sha256: d8b702bb94bb4282598eca60d283d4e90e4f969c61fd4a7a67fa5bdc9defbdc4
  size: 213672
posicionamentopl-questionamentosago2024.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/PosicionamentoPL-QuestionamentosAgo2024.pdf
  sha256: fa7b15a90aeb59baa33564cce2a2580750e372894e316d215cace510f40afedb
  size: 117091
posicionamentopl-questionamentosset2024.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/PosicionamentoPL-QuestionamentosSet2024.pdf
  sha256: 75192d0479c68f78ed33729b0dfe32b9f3857a3835de6e618c644d3b58ae7070
  size: 121890
posicionamentopl-suspensaoquestionados.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/PosicionamentoPL-SuspensaoQuestionados.pdf
  sha256: e875ddb52b31aff72ba83dc9f0a4313f76b4689c1c8f5e0b8525fe07578ad6e0
  size: 117091
relatoriotrocadns19052025.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RelatorioTrocaDNS19052025.pdf
  sha256: ed05946c7324112e61528c6b8f7af9cfe982f77bb89b0eb63838fe8bed904a6b
  size: 1045522
estrategiasepilaresjun25consol.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/EstrategiasePilaresJun25Consol.pdf
  sha256: eb9392862f0de388861a43f603315bb2e068e2be93cfa6e060a42b53d604a52c
  size: 1519397
padraoatuacaopl-dagoberto-exemplo.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/PadraoAtuacaoPL-Dagoberto-Exemplo.pdf
  sha256: 29b243777d9a4f13d0ff35f9678b2d1092083f32a9b01c707c4bdac6cd41fa2a
  size: 423160
processoqueresultouapropriacaocredito-dirceu.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ProcessoqueResultouApropriacaoCredito-Dirceu.pdf
  sha256: d129b26fa37289b15c946f0b47f267ba86f49dc606b10264b1ac06ad8b3ae628
  size: 232648
processoqueresultouapropriacaocredito-dagoberto.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ProcessoqueResultouApropriacaoCredito-Dagoberto.pdf
  sha256: 14430cc2e8415b6b46a79cf9b314dc1556adc696f97ad486cecbac95e65c75e9
  size: 129298
dez2023negociacaoinicialctorj.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/Dez2023NegociacaoInicialCtoRJ.pdf
  sha256: df8ecb5e473facec4bab61d06f405279c5df602b9616d358e5b6775a0c600c0f
  size: 83036
comunicacoesealertas-faltaatuacaopl-jur.pdf:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseAlertas-FaltaAtuaçaoPL-Jur.pdf
  sha256: 8498f85865f92576ac0fc39456cf89bfa060aeb35d6abc38643634410160f3cf
  size: 526415
analise_rj_completa.json:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/MatrizJson/analise_rj_completa.json
  sha256: 54402bff4639b6f0e278f53ca3258eff838aecef7e8315396729c7c9c6098a7d
  size: 50439
matriz_unificada_go2b_v7.json:
  path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/MatrizJson/matriz_unificada_go2b_v7.json
  sha256: 8b8e7aa7cdf19a9ab18a6208bb857e8f53540da66d745814ba1cbc8d6710477e
  size: 189172

================================================================================
FIM DOCUMENTO: go2b_lookup.json
REFERÊNCIA: doc31-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: reconciliado_go2b_lookup.json
REFERÊNCIA: doc31-referencia
PROCESSADO EM: 04/09/2025 15:08:10
HASH ORIGINAL: 14289805ab497af91173874b1c457a8baf6d2c42f7c027056b11a45fb8b4b1d7
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 7 chaves
Chaves principais:
  - tipo: str
  - arquivo: str
  - descricao: str
  - estrutura: dict
  - estatisticas: dict
  - metadata: dict
  - reconciliation_insights: dict

=== CONTEÚDO JSON ===
tipo: json
arquivo: go2b_lookup.json
descricao: Lookup table
estrutura:
  comunicacoesealertas-faltaatuacaopl-ceo.pdf:
    path: str
    sha256: str
    size: int
  dagobertopadraopl.-diversos.pdf:
    path: str
    sha256: str
    size: int
  contextoehistoricoimp.pdf:
    path: str
    sha256: str
    size: int
  peticao09062025-1039604-94.2023.8.26.0405.pdf:
    path: str
    sha256: str
    size: int
  doccen-historicocontexto.pdf:
    path: str
    sha256: str
    size: int
  contratorecupjudicial.pdf:
    path: str
    sha256: str
    size: int
  legal-document-matrix-analysis---claude.pdf:
    path: str
    sha256: str
    size: int
  legal-document-analysis-protocol---claude.pdf:
    path: str
    sha256: str
    size: int
  github-raw-files-analysis---claude.pdf:
    path: str
    sha256: str
    size: int
  detalhamentodeconteudodocumentos.txt:
    path: str
    sha256: str
    size: int
estatisticas:
  tamanho: 24835
  chaves_principais:
    [0]:
      comunicacoesealertas-faltaatuacaopl-ceo.pdf
    [1]:
      dagobertopadraopl.-diversos.pdf
    [2]:
      contextoehistoricoimp.pdf
    [3]:
      peticao09062025-1039604-94.2023.8.26.0405.pdf
    [4]:
      doccen-historicocontexto.pdf
    [5]:
      contratorecupjudicial.pdf
    [6]:
      legal-document-matrix-analysis---claude.pdf
    [7]:
      legal-document-analysis-protocol---claude.pdf
    [8]:
      github-raw-files-analysis---claude.pdf
    [9]:
      detalhamentodeconteudodocumentos.txt
  profundidade: 2
metadata:
  reconciliado_v9: True
  timestamp_reconciliacao: 2025-09-01T17:25:02.538363
  verdades_aplicadas:
    chunks: 758
    confidence: 0.85
    valores:
      apropriacao_cmz: 600000.0
      divida_ect: 387055636.47
      custas_cartas: 18000.0
      impedimento_interesse: 17000000.0
      prejuizo_total: 782655636.47
  preservacao: 100% conteudo mantido
  correcoes: 0
reconciliation_insights:
  paradoxos_encontrados:

  correcoes_aplicadas:

  informacoes_uteis:

  evidencias_preservadas:


================================================================================
FIM DOCUMENTO: reconciliado_go2b_lookup.json
REFERÊNCIA: doc31-referencia
INTEGRIDADE: VERIFICADA
================================================================================

