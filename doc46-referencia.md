# Documentos Referência para construção do doc46

**Nome In Natura:** doc46: MEGA_CONTEXT.json

**Data de Processamento:** 04/09/2025 15:08:12

**Processo RJ:** 1039604-94.2023.8.26.0405

**Inquérito MPF:** 1.16.000.001860/2025-10

**Cadeia de Custódia:** MANTIDA (Hashes SHA-256 registrados)

**Audit Log:** MEGA_AUDIT_20250904_150743.log

---

## Temática do Documento

O **doc46** trata do tema: **Contexto MEGA e metadados de processamento**

Os documentos abaixo são utilizados como **referência para extração desta temática específica**, não para uso integral. A referência pode conter múltiplos temas e complexidades, podendo apresentar duplicidades que serão tratadas nas fases posteriores.

## Controles de Segurança e Auditoria

- **Backup de Segurança:** Criado antes do processamento
- **Hashes de Integridade:** Calculados para todos os arquivos
- **Log de Auditoria:** Todas as operações registradas
- **Normalização UTF-8:** Aplicada preservando conteúdo original
- **Classificação LGPD:** Documentos classificados por sensibilidade

---

## Arquivos/Documentos Utilizados como Referência

1. `MEGA_CONTEXT.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `8728fbc6dc8de7dd5df1b668fe92a7198ee47890ef674812a61166a35066ddca`
   - Sensibilidade: ALTA_SENSIBILIDADE

2. `analysis_MEGA_CONTEXT.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `f94b8dac747f9b5c715e90cbdb038d6b8659aa5f0dffb7c3ddb1aae78cddaf8c`
   - Sensibilidade: ALTA_SENSIBILIDADE

3. `analysis_MEGA_CONTEXT_20250826_203959.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `f12c89ac6e5088dd7851f6cbd99bf6bd6043fa3259a241e6ff036d5a445e5a77`
   - Sensibilidade: ALTA_SENSIBILIDADE

4. `reconciliado_MEGA_CONTEXT.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `ae3bfdf5763ee0bc020c565203fec79bcda07e966827cfe547dbb4d431294cb1`
   - Sensibilidade: ALTA_SENSIBILIDADE

---

\newpage

================================================================================
DOCUMENTO: MEGA_CONTEXT.json
REFERÊNCIA: doc46-referencia
PROCESSADO EM: 04/09/2025 15:08:12
HASH ORIGINAL: 8728fbc6dc8de7dd5df1b668fe92a7198ee47890ef674812a61166a35066ddca
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 9 chaves
Chaves principais:
  - created_at: str
  - system_prompt: str
  - key_numbers: dict
  - matrix_findings: list
  - hybrid_comms: str
  - proto_mestre_v2: str
  - annexes_digest: list
  - evidence: list
  - messages: list

=== CONTEÚDO JSON ===
created_at: 2025-08-26 09:22:58
system_prompt: Você é um assistente jurídico/técnico focado no dossiê GO2B. Use EXCLUSIVAMENTE as evidências abaixo; cite o item [01], [02] etc. Se faltar base, escreva literalmente: 'FALTA EVIDÊNCIA PARA: ...'. Estru... [TRUNCADO]
key_numbers:
  num_docs: 78
  violacoes: 20
  provas: 32
matrix_findings:
  [0]:
    Omissão/degradação do crédito ECT-Correios nas peças principais [referencie [n]].
  [1]:
    Autofalência ventilada sem documentos obrigatórios anexos.
  [2]:
    Menções/indícios de crime e necessidade de saneamento probatório.
hybrid_comms: Plano de Comunicações Híbrido (digital-first + físico residual):
- **Base legal**: economicidade, ampla publicidade e efetividade; quando houver dúvida de entrega digital, complementar via AR físico d... [TRUNCADO]
proto_mestre_v2: - Checagens iniciais:
  1) No do processo e classe; 2) Representação vigente (Petição 09/06/2025) [n];
  3) Marco 19/05/2025 (DNS/renúncia) [n]; 4) Ato do AJ em 28/05/2025 [n];
  5) MPF 20–22/08/2025 ... [TRUNCADO]
annexes_digest:
  [0]:
    name: anexo_degradacao.png
    path: anexo_degradacao.png
    size_bytes: 72267
    mtime: 2025-08-26 09:22:58
    sha256: b66874d8f48a4cbab35e830cc90df725bb30a5d18bf3746ce760cfabf95d6820
    description: Gráfico de degradação documental (indicativo)
  [1]:
    name: anexo_fluxo_dinheiro.png
    path: anexo_fluxo_dinheiro.png
    size_bytes: 29155
    mtime: 2025-08-26 09:22:58
    sha256: 86814b44e86fee4691504f67cbd1c0851889b48357be5c5d1fb9f96af4aa41ab
    description: Fluxo do dinheiro (ECT→AJ→PL/GO2B/Terceiros)
  [2]:
    name: anexo_tabela_violacoes.csv
    path: anexo_tabela_violacoes.csv
    size_bytes: 170365
    mtime: 2025-08-26 09:22:58
    sha256: ef5bfa67deb565def52b159ab36bd1627048cbbe46f4c7ea25dcdb78c1a78bb5
    description: Tabela de violações mapeadas
    csv_preview:
      header:
        [0]:
          arquivo
        [1]:
          secao
        [2]:
          descricao
      rows:
        [0]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [1]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [2]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [3]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [4]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [5]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [6]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [7]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [8]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [9]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [10]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [11]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [12]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [13]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [14]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [15]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [16]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [17]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [18]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [19]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [20]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [21]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [22]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [23]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [24]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [25]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [26]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [27]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [28]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [29]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [30]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [31]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [32]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [33]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [34]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [35]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [36]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [37]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [38]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [39]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
evidence:
  [0]:
    n: 01
    id: go2b::008993
    title: documentosbaseconhecimento.txt
    section: full
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosbaseconhecimento.txt
    source_sha256: 539771468b44f8cc30d002897df7b502ee950699e99e54ca37731fcfe98ec3e9
    snippet: tode prestaçãode serviçosdeTrade Marketing,naquala Goiásofertava segurosestipulados porparceirosda Chubb,ficando aindaresponsável pelaguardaeenvio daspropostasde adesõesaosseguros. Numprazode5 anos,se... [TRUNCADO]
  [1]:
    n: 02
    id: go2b::002406
    title: todosfusao.txt
    section: full
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.txt
    source_sha256: 545d0c66c8ac553d86e0d70cfc1796053ff95c38999b94a823ba00abf120d7be
    snippet: rvi√ßosLtda S√çNTESEDO PROCESSO: Ajuizoua√ß√£o declarat√≥riade inexist√TMnciade d√©bitoe inexigibilidadede t√≠tulocompedidode suspens√£odos efeitosdeprotesto. Alegaquearela√ß√£o entreaspartesteve in√≠c... [TRUNCADO]
  [2]:
    n: 03
    id: go2b::004253
    title: todosfusao.pdf
    section: page:855
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.pdf
    source_sha256: bdd86800904c452cd3064be787b165ff128732d840e4031b62907c518b383a81
    snippet: ua todas as cópias de seu sistema de computadores sem ler, salvar, imprimir, encaminhar ou utilizá-las de qualquer maneira. Apesar de ter sido verificado para identificar eventuais vírus e outros soft... [TRUNCADO]
  [3]:
    n: 04
    id: go2b::000077
    title: ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
    section: page:38
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
    source_sha256: f0b272a16c5efdb509f03afc3465dd6ecf24c0c583ce696cc0a04ab7c3e68769
    snippet: ua todas as cópias de seu sistema de computadores sem ler, salvar, imprimir, encaminhar ou utilizá-las de qualquer maneira. Apesar de ter sido verificado para identificar eventuais vírus e outros soft... [TRUNCADO]
  [4]:
    n: 05
    id: go2b::009139
    title: documentosbaseconhecimento.pdf
    section: page:38
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/documentosbaseconhecimento.pdf
    source_sha256: 54118726f5790f80a5515c41add7834e2b1257a261434c30ab8f9a62dc6417d4
    snippet: ua todas as cópias de seu sistema de computadores sem ler, salvar, imprimir, encaminhar ou utilizá-las de qualquer maneira. Apesar de ter sido verificado para identificar eventuais vírus e outros soft... [TRUNCADO]
  [5]:
    n: 06
    id: go2b::005333
    title: chatsclaudeprojeto.txt
    section: full
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaudeprojeto.txt
    source_sha256: 8770a1d35a71f61174c58492fd2055240cf6ea61142db0ff9ab31f6f5e04e953
    snippet: entetravado Memóriaacimade8GB Mensagem "Killed" aparecer CPUem0% PLANOB(setravar): Sedemorarmaisde30minutosoutravar,podemos: 1. Interromper(Ctrl+C) 2. Processaroarquivograndeseparadamentecomoutrométod... [TRUNCADO]
  [6]:
    n: 07
    id: go2b::000305
    title: Legal Document Matrix Analysis - Claude.pdf
    section: page:9
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Legal Document Matrix Analysis - Claude.pdf
    source_sha256: 53714691749d482a8f32eb37e7c53ee58e269cab0f1b8ea39d3dd4dd80ba3b68
    snippet: print(f"SHA-256: {file_hash}") print(f"Size: {os.path.getsize(filename):,} bytes") return filename, file_hash def query(self, query_type: str, query_value: Any) -> Any: """Sistema de consulta rápida""... [TRUNCADO]
  [7]:
    n: 08
    id: go2b::005990
    title: artefatos.txt
    section: full
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/artefatos.txt
    source_sha256: 512384296e4082db815d850455b66db77e7117ca6b3a21b213faeb91cf8daca9
    snippet: 
  [8]:
    n: 09
    id: go2b::000300
    title: Legal Document Matrix Analysis - Claude.pdf
    section: page:7
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Legal Document Matrix Analysis - Claude.pdf
    source_sha256: 53714691749d482a8f32eb37e7c53ee58e269cab0f1b8ea39d3dd4dd80ba3b68
    snippet: damages": { "direct": { "ect_credit": 387055636.47, "pl_appropriation": 600000, "denied_savings": 18337.90, "judicial_blocks": 15000000, "labor_fines": 45000000, "subtotal": 447655636.47 }, "indirect"... [TRUNCADO]
  [9]:
    n: 10
    id: go2b::010474
    title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
    section: page:195
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
    source_sha256: 30c3db760ca2d0d412438669aecf03d6764faebeb9cb48bc71968b1645252424
    snippet: • NF12 -REPACTEMITIR: Item de Cobrança Valor Bruto Link Integrado -Memoriais NF01 -PENDPAGAMENTO R$ 18.553.608,25 NF0205 -FATPENDENTE(CAUTELAR) R$ 28.312.489,40 NF06 -HSDIVEDSR R$ 12.244.009,31 NF07 -... [TRUNCADO]
  [10]:
    n: 11
    id: go2b::007588
    title: artefatos.pdf
    section: page:394
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/artefatos.pdf
    source_sha256: 66bd9ec71221728dbbefa3c914d08d830617e2d33620521104b2258b7d6b6a07
    snippet: • NF12 -REPACTEMITIR: Item de Cobrança Valor Bruto Link Integrado -Memoriais NF01 -PENDPAGAMENTO R$ 18.553.608,25 NF0205 -FATPENDENTE(CAUTELAR) R$ 28.312.489,40 NF06 -HSDIVEDSR R$ 12.244.009,31 NF07 -... [TRUNCADO]
  [11]:
    n: 12
    id: go2b::003296
    title: todosfusao.pdf
    section: page:394
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.pdf
    source_sha256: bdd86800904c452cd3064be787b165ff128732d840e4031b62907c518b383a81
    snippet: • NF12 -REPACTEMITIR: Item de Cobrança Valor Bruto Link Integrado -Memoriais NF01 -PENDPAGAMENTO R$ 18.553.608,25 NF0205 -FATPENDENTE(CAUTELAR) R$ 28.312.489,40 NF06 -HSDIVEDSR R$ 12.244.009,31 NF07 -... [TRUNCADO]
  [12]:
    n: 13
    id: go2b::010817
    title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
    section: page:137
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
    source_sha256: a4705c43de3ee368172575ac27d9b19a02591ec556262646d7f169586cbde3e4
    snippet: Jardim da Silva, ONLOG; Sergio Eduardo Roda Junior, ONLOG; José Furian Filho, ONLOG/Sinerlog; José Carlos da Rocha Lima, ONLOG; Helder Braz Jardim da Silva, NOSS/ONLOG; Alessandro Esteves da Silva, Su... [TRUNCADO]
  [13]:
    n: 14
    id: go2b::007166
    title: artefatos.pdf
    section: page:190
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/artefatos.pdf
    source_sha256: 66bd9ec71221728dbbefa3c914d08d830617e2d33620521104b2258b7d6b6a07
    snippet: Jardim da Silva, ONLOG; Sergio Eduardo Roda Junior, ONLOG; José Furian Filho, ONLOG/Sinerlog; José Carlos da Rocha Lima, ONLOG; Helder Braz Jardim da Silva, NOSS/ONLOG; Alessandro Esteves da Silva, Su... [TRUNCADO]
  [14]:
    n: 15
    id: go2b::002874
    title: todosfusao.pdf
    section: page:190
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.pdf
    source_sha256: bdd86800904c452cd3064be787b165ff128732d840e4031b62907c518b383a81
    snippet: Jardim da Silva, ONLOG; Sergio Eduardo Roda Junior, ONLOG; José Furian Filho, ONLOG/Sinerlog; José Carlos da Rocha Lima, ONLOG; Helder Braz Jardim da Silva, NOSS/ONLOG; Alessandro Esteves da Silva, Su... [TRUNCADO]
  [15]:
    n: 16
    id: go2b::000070
    title: ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
    section: page:33
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
    source_sha256: f0b272a16c5efdb509f03afc3465dd6ecf24c0c583ce696cc0a04ab7c3e68769
    snippet: 33 <pitney.operacoes07@chubb.com >; Chubb Expedição Brazil < expedicao.br@chubb.com > Assunto: RES: FATURA - BANCO ABC BRASIL - GOIAS BUSINESS @Sueto, Simone Y , Notei que já fizemos alguns pagamentos... [TRUNCADO]
  [16]:
    n: 17
    id: go2b::004246
    title: todosfusao.pdf
    section: page:850
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.pdf
    source_sha256: bdd86800904c452cd3064be787b165ff128732d840e4031b62907c518b383a81
    snippet: 33 <pitney.operacoes07@chubb.com >; Chubb Expedição Brazil < expedicao.br@chubb.com > Assunto: RES: FATURA - BANCO ABC BRASIL - GOIAS BUSINESS @Sueto, Simone Y , Notei que já fizemos alguns pagamentos... [TRUNCADO]
  [17]:
    n: 18
    id: go2b::000302
    title: Legal Document Matrix Analysis - Claude.pdf
    section: page:8
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Legal Document Matrix Analysis - Claude.pdf
    source_sha256: 53714691749d482a8f32eb37e7c53ee58e269cab0f1b8ea39d3dd4dd80ba3b68
    snippet: }, "contractual_violations": { "query": "contract violations count", "answer": "6 clauses systematically violated" }, "impediment_proof": { "query": "impediment evidence", "answer": "Kinship + R$ 17M ... [TRUNCADO]
  [18]:
    n: 19
    id: go2b::009132
    title: documentosbaseconhecimento.pdf
    section: page:33
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/documentosbaseconhecimento.pdf
    source_sha256: 54118726f5790f80a5515c41add7834e2b1257a261434c30ab8f9a62dc6417d4
    snippet: 33 <pitney.operacoes07@chubb.com >; Chubb Expedição Brazil < expedicao.br@chubb.com > Assunto: RES: FATURA - BANCO ABC BRASIL - GOIAS BUSINESS @Sueto, Simone Y , Notei que já fizemos alguns pagamentos... [TRUNCADO]
  [19]:
    n: 20
    id: go2b::008181
    title: Projeto Knowledge Document Review - Claude.pdf
    section: page:15
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto Knowledge Document Review - Claude.pdf
    source_sha256: 1f801a952593ebae43efb1bb1dd40cf333d51fc908714925c52c070df85998f6
    snippet: O PROBLEMA IDENTIFICADO: Os resultados vazios indicam que: 1. Os caminhos dos diretórios estão incorretos 2. Ou os PDFs não estão nesses diretórios EXECUTE ESTE COMANDO PRIMEIRO para verificar: Execut... [TRUNCADO]
  [20]:
    n: 21
    id: go2b::007457
    title: artefatos.pdf
    section: page:334
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/artefatos.pdf
    source_sha256: 66bd9ec71221728dbbefa3c914d08d830617e2d33620521104b2258b7d6b6a07
    snippet: berativo – Edgard de Aguiar Cordeiro; Membro eleita do Conselho Deliberativo – Amanda Gomes Corcino; e Membro eleito do Conselho Deliberativo – Anézio Rodrigues; c.8) dos seguintes cidadãos, ocupantes... [TRUNCADO]
  [21]:
    n: 22
    id: go2b::006719
    title: chatsclaudeprojeto.pdf
    section: page:219
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/chatsclaudeprojeto.pdf
    source_sha256: ac73565b36e7cc8e195d0a1196dea8ea4ee6724902c959ce1c4ccca4008f7b81
    snippet: O PROBLEMA IDENTIFICADO: Os resultados vazios indicam que: 1. Os caminhos dos diretórios estão incorretos 2. Ou os PDFs não estão nesses diretórios EXECUTE ESTE COMANDO PRIMEIRO para verificar: Execut... [TRUNCADO]
  [22]:
    n: 23
    id: go2b::000169
    title: ContextoeHistoricoImp.pdf
    section: page:20
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ContextoeHistoricoImp.pdf
    source_sha256: 9d77128c18f635ed6370562c9a60d47da676820885167e61d83071d16d0076db
    snippet: 7L<# .=)58%698!#5LJJ "#9 !!%"$%!%"FG()*+H)$)?-@)(FG3)HA3.A*B+?$!!%"$%!%"56"778!J#55";%!%6$!! %!%<5<!775"!<6J#6!!"8 .=)%<68655LJ" .=)6866%8#66LJ9 <5% !!%7$%!%6FG()*+H)$)@H)C3.H20B3)FM(.F@3$!!%7$%!%656"... [TRUNCADO]
  [23]:
    n: 24
    id: go2b::009800
    title: documentosbaseconhecimento.pdf
    section: page:349
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/documentosbaseconhecimento.pdf
    source_sha256: 54118726f5790f80a5515c41add7834e2b1257a261434c30ab8f9a62dc6417d4
    snippet: 05/06/2025, 17:21Gerenciamento de conta - Registro.br As mensagens abaixo são referentes a erros que podem ocorrer no DS: FAIL - Erro/Falha no DNS - Ocorreu um erro na comunicação com o servidor DNS.•... [TRUNCADO]
  [24]:
    n: 25
    id: go2b::010343
    title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
    section: page:135
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
    source_sha256: 30c3db760ca2d0d412438669aecf03d6764faebeb9cb48bc71968b1645252424
    snippet: berativo – Edgard de Aguiar Cordeiro; Membro eleita do Conselho Deliberativo – Amanda Gomes Corcino; e Membro eleito do Conselho Deliberativo – Anézio Rodrigues; c.8) dos seguintes cidadãos, ocupantes... [TRUNCADO]
  [25]:
    n: 26
    id: go2b::000308
    title: Legal Document Matrix Analysis - Claude.pdf
    section: page:10
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Legal Document Matrix Analysis - Claude.pdf
    source_sha256: 53714691749d482a8f32eb37e7c53ee58e269cab0f1b8ea39d3dd4dd80ba3b68
    snippet: Este script Python gera: 1. JSON estruturado com toda base de conhecimento indexada 2. Sistema de consultas por data, ator, violação, valor 3. Motor de inferência para urgência e estratégias 4. Índice... [TRUNCADO]
  [26]:
    n: 27
    id: go2b::009626
    title: documentosbaseconhecimento.pdf
    section: page:240
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/documentosbaseconhecimento.pdf
    source_sha256: 54118726f5790f80a5515c41add7834e2b1257a261434c30ab8f9a62dc6417d4
    snippet: Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 – Brasília / DF Tels: +55 61 3303-1717/3303-3117 Willians Cristiano Marques, Melhor Envio; Tiago Vicente Alv... [TRUNCADO]
  [27]:
    n: 28
    id: go2b::011140
    title: MPF-JuntadaAutosECT-Completo-vs25082025.pdf
    section: page:49
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/MPF-JuntadaAutosECT-Completo-vs25082025.pdf
    source_sha256: 6d06824add65dd5fe5a51f6aab6ade27816ffed98d74d56acbb93e4432469eec
    snippet: Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 – Brasília / DF Tels: +55 61 3303-1717/3303-3117 Willians Cristiano Marques, Melhor Envio; Tiago Vicente Alv... [TRUNCADO]
  [28]:
    n: 29
    id: go2b::011250
    title: RelatorioTrocaDNS19052025.pdf
    section: page:13
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RelatorioTrocaDNS19052025.pdf
    source_sha256: ed05946c7324112e61528c6b8f7af9cfe982f77bb89b0eb63838fe8bed904a6b
    snippet: 05/06/2025, 17:21Gerenciamento de conta - Registro.br As mensagens abaixo são referentes a erros que podem ocorrer no DS: FAIL - Erro/Falha no DNS - Ocorreu um erro na comunicação com o servidor DNS.•... [TRUNCADO]
  [29]:
    n: 30
    id: go2b::011453
    title: ComunicacoeseAlertas-FaltaAtuaçaoPL-Jur.pdf
    section: page:3
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseAlertas-FaltaAtuaçaoPL-Jur.pdf
    source_sha256: 8498f85865f92576ac0fc39456cf89bfa060aeb35d6abc38643634410160f3cf
    snippet: a - Goias Business Consultoria e Serviços Ltda - FLY RECUPERAÇÕES EMPRESARIAIS LTDA - BANCO BRADESCO S/A - - Caixa Econômica Federal - - Banco do Brasil S/A - - Banco ABC Brasil S.A. - - Itaú Unibanco... [TRUNCADO]
  [30]:
    n: 31
    id: go2b::010344
    title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
    section: page:136
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
    source_sha256: 30c3db760ca2d0d412438669aecf03d6764faebeb9cb48bc71968b1645252424
    snippet: SF/25122.07839-60 Assinado eletronicamente, por Sen. Flávio Bolsonaro Para verificar as assinaturas, acesse Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 ... [TRUNCADO]
  [31]:
    n: 32
    id: go2b::007458
    title: artefatos.pdf
    section: page:335
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/artefatos.pdf
    source_sha256: 66bd9ec71221728dbbefa3c914d08d830617e2d33620521104b2258b7d6b6a07
    snippet: SF/25122.07839-60 Assinado eletronicamente, por Sen. Flávio Bolsonaro Para verificar as assinaturas, acesse Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 ... [TRUNCADO]
  [32]:
    n: 33
    id: go2b::011684
    title: matriz_unificada_go2b_v7.json
    section: json
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/MatrizJson/matriz_unificada_go2b_v7.json
    source_sha256: 8b8e7aa7cdf19a9ab18a6208bb857e8f53540da66d745814ba1cbc8d6710477e
    snippet: 03]/id", "type_conflict": { "left_type": "str", "right_type": "str" }, "kept_richness": [ 1, 7 ] }, { "path": "events/[id=evt_003]/date", "type_conflict": { "left_type": "str", "right_type": "str" }, ... [TRUNCADO]
  [33]:
    n: 34
    id: go2b::006764
    title: chatsclaudeprojeto.pdf
    section: page:236
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/chatsclaudeprojeto.pdf
    source_sha256: ac73565b36e7cc8e195d0a1196dea8ea4ee6724902c959ce1c4ccca4008f7b81
    snippet: 1. VERIFIQUE A MEMÓRIA E CPU: Procure pelo processo Python - deve estar usando bastante memória (provavelmente 2-4 GB). 2. VERIFIQUE SE ESTÁ CRIANDO ARQUIVOS PARCIAIS: 3. ESTIMATIVA DE TEMPO: 450 MB c... [TRUNCADO]
  [34]:
    n: 35
    id: go2b::008226
    title: Projeto Knowledge Document Review - Claude.pdf
    section: page:32
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto Knowledge Document Review - Claude.pdf
    source_sha256: 1f801a952593ebae43efb1bb1dd40cf333d51fc908714925c52c070df85998f6
    snippet: 1. VERIFIQUE A MEMÓRIA E CPU: Procure pelo processo Python - deve estar usando bastante memória (provavelmente 2-4 GB). 2. VERIFIQUE SE ESTÁ CRIANDO ARQUIVOS PARCIAIS: 3. ESTIMATIVA DE TEMPO: 450 MB c... [TRUNCADO]
  [35]:
    n: 36
    id: go2b::006732
    title: chatsclaudeprojeto.pdf
    section: page:224
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/chatsclaudeprojeto.pdf
    source_sha256: ac73565b36e7cc8e195d0a1196dea8ea4ee6724902c959ce1c4ccca4008f7b81
    snippet: print(f" • Menções crime falimentar: {analyzer.stats['mencoes_crime']}") print(f" • Menções R$ 387 milhões: {analyzer.stats['mencoes_387mi']}") print(f" • Erros encontrados: {len(analyzer.errors)}") p... [TRUNCADO]
  [36]:
    n: 37
    id: go2b::008194
    title: Projeto Knowledge Document Review - Claude.pdf
    section: page:20
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto Knowledge Document Review - Claude.pdf
    source_sha256: 1f801a952593ebae43efb1bb1dd40cf333d51fc908714925c52c070df85998f6
    snippet: print(f" • Menções crime falimentar: {analyzer.stats['mencoes_crime']}") print(f" • Menções R$ 387 milhões: {analyzer.stats['mencoes_387mi']}") print(f" • Erros encontrados: {len(analyzer.errors)}") p... [TRUNCADO]
  [37]:
    n: 38
    id: go2b::006707
    title: chatsclaudeprojeto.pdf
    section: page:214
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/chatsclaudeprojeto.pdf
    source_sha256: ac73565b36e7cc8e195d0a1196dea8ea4ee6724902c959ce1c4ccca4008f7b81
    snippet: INSTRUÇÕES PARA USAR: 1. Instale as dependências: 2. Obtenha uma API key da Anthropic: Crie uma API key Substitua no script 3. Execute o script: 4. Traga os resultados para cá: O script gerará arquivo... [TRUNCADO]
  [38]:
    n: 39
    id: go2b::008169
    title: Projeto Knowledge Document Review - Claude.pdf
    section: page:10
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto Knowledge Document Review - Claude.pdf
    source_sha256: 1f801a952593ebae43efb1bb1dd40cf333d51fc908714925c52c070df85998f6
    snippet: INSTRUÇÕES PARA USAR: 1. Instale as dependências: 2. Obtenha uma API key da Anthropic: Crie uma API key Substitua no script 3. Execute o script: 4. Traga os resultados para cá: O script gerará arquivo... [TRUNCADO]
  [39]:
    n: 40
    id: go2b::010361
    title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
    section: page:143
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
    source_sha256: 30c3db760ca2d0d412438669aecf03d6764faebeb9cb48bc71968b1645252424
    snippet: presálias”, segue a denúncia. MAIS LIDASEm 11 de junho de 2023, por exemplo, há uma mensagem do dirigente pedindoemprego para uma mulher. “Atualmente ela é minha companheira e, portanto, nãopoderia la... [TRUNCADO]
  [40]:
    n: 41
    id: go2b::000131
    title: ContextoeHistoricoImp.pdf
    section: page:7
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ContextoeHistoricoImp.pdf
    source_sha256: 9d77128c18f635ed6370562c9a60d47da676820885167e61d83071d16d0076db
    snippet: para o momento, mas saiba que sobrevivo hoje de emprés6mos de familiares e venda de objetos par6culares (Até vídeo game do meu filho vendi). Adiciono situações especificas como a interrupção de tratamen... [TRUNCADO]
  [41]:
    n: 42
    id: go2b::000380
    title: GitHub Raw Files Analysis - Claude.pdf
    section: page:23
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/GitHub Raw Files Analysis - Claude.pdf
    source_sha256: dbdbb765bb194d677e0a05b4ffcc075c0828e0b7b47744de0a836bff67e620fd
    snippet: Venda de todos os bens pessoais Dependência de caridade familiar 17.2. IMPACTO NOS 6.000 TRABALHADORES DADOS SOCIAIS CRÍTICOS: 6.000 famílias sem renda Aproximadamente 24.000 pessoas afetadas 85% dos ... [TRUNCADO]
  [42]:
    n: 43
    id: go2b::011138
    title: MPF-JuntadaAutosECT-Completo-vs25082025.pdf
    section: page:48
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/MPF-JuntadaAutosECT-Completo-vs25082025.pdf
    source_sha256: 6d06824add65dd5fe5a51f6aab6ade27816ffed98d74d56acbb93e4432469eec
    snippet: Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 – Brasília / DF Tels: +55 61 3303-1717/3303-3117 c.6) dos seguintes cidadãos, ocupantes e ex-ocupantes de ca... [TRUNCADO]
  [43]:
    n: 44
    id: go2b::011136
    title: MPF-JuntadaAutosECT-Completo-vs25082025.pdf
    section: page:47
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/MPF-JuntadaAutosECT-Completo-vs25082025.pdf
    source_sha256: 6d06824add65dd5fe5a51f6aab6ade27816ffed98d74d56acbb93e4432469eec
    snippet: Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 – Brasília / DF Tels: +55 61 3303-1717/3303-3117 b.3) Ministra da Gestão e Inovação em Serviços Públicos; c)... [TRUNCADO]
  [44]:
    n: 45
    id: go2b::010834
    title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
    section: page:144
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
    source_sha256: a4705c43de3ee368172575ac27d9b19a02591ec556262646d7f169586cbde3e4
    snippet: nstrado que essa postura não visava resolver efetivamente ainadimplência da ECT, mas sim criar um ambiente de confiança artificial parainduzir a GO2B a contratar terceirizados indicados por interesses... [TRUNCADO]
  [45]:
    n: 46
    id: go2b::010816
    title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
    section: page:136
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
    source_sha256: a4705c43de3ee368172575ac27d9b19a02591ec556262646d7f169586cbde3e4
    snippet: s e funções no Postalis: presidente, Camilo Fernandes dos Santos; ex-presidente do Postalis, Antônio Carlos Conquista; ex-presidente do Postalis,; Membro indicado do Conselho Deliberativo – Hudson Alv... [TRUNCADO]
  [46]:
    n: 47
    id: go2b::008423
    title: Matrix Integration and Knowledge Maximization - Claude.pdf
    section: page:11
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Matrix Integration and Knowledge Maximization - Claude.pdf
    source_sha256: 209d5ffe6e9f5cc851e29645c7b9884b0365dc05a44d92cf2a475b2a470843fb
    snippet: "total_characters_processed": 15762027, "confidence_overall": 0.99, "consistency_checks": [ "timezone_normalized: America/Sao_Paulo", "ids_crosslinked: events<->evidence<->violations<->remedies", "dup... [TRUNCADO]
  [47]:
    n: 48
    id: go2b::011238
    title: RelatorioTrocaDNS19052025.pdf
    section: page:7
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RelatorioTrocaDNS19052025.pdf
    source_sha256: ed05946c7324112e61528c6b8f7af9cfe982f77bb89b0eb63838fe8bed904a6b
    snippet: 05/06/2025, 17:21Gerenciamento de conta - Registro.br 3. Token O que é o token? Um segundo fator de segurança para acesso ao nosso sistema, conhecido também como "Verificação em Duas Etapas". Seu uso ... [TRUNCADO]
  [48]:
    n: 49
    id: go2b::011248
    title: RelatorioTrocaDNS19052025.pdf
    section: page:12
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RelatorioTrocaDNS19052025.pdf
    source_sha256: ed05946c7324112e61528c6b8f7af9cfe982f77bb89b0eb63838fe8bed904a6b
    snippet: 05/06/2025, 17:21Gerenciamento de conta - Registro.br CCU Unicamp(Português) LDP DNS-HOWTO Literatura P. Albitz, C. Liu, "DNS and BIND, 4th. edition", OReilly & Associates, Inc. - ISBN: 0596001584 Qua... [TRUNCADO]
  [49]:
    n: 50
    id: go2b::011252
    title: RelatorioTrocaDNS19052025.pdf
    section: page:14
    source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RelatorioTrocaDNS19052025.pdf
    source_sha256: ed05946c7324112e61528c6b8f7af9cfe982f77bb89b0eb63838fe8bed904a6b
    snippet: 05/06/2025, 17:21Gerenciamento de conta - Registro.br Como um dos contatos mencionados acima, acesse o sistema com seu Usuário e senha e selecione o nome do domínio. Na tela seguinte, você terá acesso... [TRUNCADO]
  [... +170 itens omitidos]
messages:
  [0]:
    role: system
    content: Você é um assistente jurídico/técnico focado no dossiê GO2B. Use EXCLUSIVAMENTE as evidências abaixo; cite o item [01], [02] etc. Se faltar base, escreva literalmente: 'FALTA EVIDÊNCIA PARA: ...'. Estru... [TRUNCADO]
  [1]:
    role: system
    content: POLÍTICA: Todo fato deve citar [no do item]. Onde faltar, escrever: 'FALTA EVIDÊNCIA PARA: ...'.
  [2]:
    role: user
    content: Use apenas as evidências listadas abaixo, citando [no do item].

================================================================================
FIM DOCUMENTO: MEGA_CONTEXT.json
REFERÊNCIA: doc46-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: analysis_MEGA_CONTEXT.json
REFERÊNCIA: doc46-referencia
PROCESSADO EM: 04/09/2025 15:08:12
HASH ORIGINAL: f94b8dac747f9b5c715e90cbdb038d6b8659aa5f0dffb7c3ddb1aae78cddaf8c
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
  file: MEGA_CONTEXT.json
  path: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/desenvolvimentos_outros/MEGA_CONTEXT.json
  timestamp: 2025-09-01T16:38:11.737143
  size: 407049
  type: json
  descricao: 
  is_critical: False
  preservacao: 100% conteudo mantido
content_extraction:
  success: True
  full_content:
    created_at: 2025-08-26 09:22:58
    system_prompt: Você é um assistente jurídico/técnico focado no dossiê GO2B. Use EXCLUSIVAMENTE as evidências abaixo; cite o item [01], [02] etc. Se faltar base, escreva literalmente: 'FALTA EVIDÊNCIA PARA: ...'. Estru... [TRUNCADO]
    key_numbers:
      num_docs: 78
      violacoes: 20
      provas: 32
    matrix_findings:
      [0]:
        Omissão/degradação do crédito ECT-Correios nas peças principais [referencie [n]].
      [1]:
        Autofalência ventilada sem documentos obrigatórios anexos.
      [2]:
        Menções/indícios de crime e necessidade de saneamento probatório.
    hybrid_comms: Plano de Comunicações Híbrido (digital-first + físico residual):
- **Base legal**: economicidade, ampla publicidade e efetividade; quando houver dúvida de entrega digital, complementar via AR físico d... [TRUNCADO]
    proto_mestre_v2: - Checagens iniciais:
  1) No do processo e classe; 2) Representação vigente (Petição 09/06/2025) [n];
  3) Marco 19/05/2025 (DNS/renúncia) [n]; 4) Ato do AJ em 28/05/2025 [n];
  5) MPF 20–22/08/2025 ... [TRUNCADO]
    annexes_digest:
      [0]:
        name: anexo_degradacao.png
        path: anexo_degradacao.png
        size_bytes: 72267
        mtime: 2025-08-26 09:22:58
        sha256: b66874d8f48a4cbab35e830cc90df725bb30a5d18bf3746ce760cfabf95d6820
        description: Gráfico de degradação documental (indicativo)
      [1]:
        name: anexo_fluxo_dinheiro.png
        path: anexo_fluxo_dinheiro.png
        size_bytes: 29155
        mtime: 2025-08-26 09:22:58
        sha256: 86814b44e86fee4691504f67cbd1c0851889b48357be5c5d1fb9f96af4aa41ab
        description: Fluxo do dinheiro (ECT→AJ→PL/GO2B/Terceiros)
      [2]:
        name: anexo_tabela_violacoes.csv
        path: anexo_tabela_violacoes.csv
        size_bytes: 170365
        mtime: 2025-08-26 09:22:58
        sha256: ef5bfa67deb565def52b159ab36bd1627048cbbe46f4c7ea25dcdb78c1a78bb5
        description: Tabela de violações mapeadas
        csv_preview:
          header:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          rows:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
    evidence:
      [0]:
        n: 01
        id: go2b::008993
        title: documentosbaseconhecimento.txt
        section: full
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosbaseconhecimento.txt
        source_sha256: 539771468b44f8cc30d002897df7b502ee950699e99e54ca37731fcfe98ec3e9
        snippet: tode prestaçãode serviçosdeTrade Marketing,naquala Goiásofertava segurosestipulados porparceirosda Chubb,ficando aindaresponsável pelaguardaeenvio daspropostasde adesõesaosseguros. Numprazode5 anos,se... [TRUNCADO]
      [1]:
        n: 02
        id: go2b::002406
        title: todosfusao.txt
        section: full
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.txt
        source_sha256: 545d0c66c8ac553d86e0d70cfc1796053ff95c38999b94a823ba00abf120d7be
        snippet: rvi√ßosLtda S√çNTESEDO PROCESSO: Ajuizoua√ß√£o declarat√≥riade inexist√TMnciade d√©bitoe inexigibilidadede t√≠tulocompedidode suspens√£odos efeitosdeprotesto. Alegaquearela√ß√£o entreaspartesteve in√≠c... [TRUNCADO]
      [2]:
        n: 03
        id: go2b::004253
        title: todosfusao.pdf
        section: page:855
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.pdf
        source_sha256: bdd86800904c452cd3064be787b165ff128732d840e4031b62907c518b383a81
        snippet: ua todas as cópias de seu sistema de computadores sem ler, salvar, imprimir, encaminhar ou utilizá-las de qualquer maneira. Apesar de ter sido verificado para identificar eventuais vírus e outros soft... [TRUNCADO]
      [3]:
        n: 04
        id: go2b::000077
        title: ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
        section: page:38
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
        source_sha256: f0b272a16c5efdb509f03afc3465dd6ecf24c0c583ce696cc0a04ab7c3e68769
        snippet: ua todas as cópias de seu sistema de computadores sem ler, salvar, imprimir, encaminhar ou utilizá-las de qualquer maneira. Apesar de ter sido verificado para identificar eventuais vírus e outros soft... [TRUNCADO]
      [4]:
        n: 05
        id: go2b::009139
        title: documentosbaseconhecimento.pdf
        section: page:38
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/documentosbaseconhecimento.pdf
        source_sha256: 54118726f5790f80a5515c41add7834e2b1257a261434c30ab8f9a62dc6417d4
        snippet: ua todas as cópias de seu sistema de computadores sem ler, salvar, imprimir, encaminhar ou utilizá-las de qualquer maneira. Apesar de ter sido verificado para identificar eventuais vírus e outros soft... [TRUNCADO]
      [5]:
        n: 06
        id: go2b::005333
        title: chatsclaudeprojeto.txt
        section: full
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaudeprojeto.txt
        source_sha256: 8770a1d35a71f61174c58492fd2055240cf6ea61142db0ff9ab31f6f5e04e953
        snippet: entetravado Memóriaacimade8GB Mensagem "Killed" aparecer CPUem0% PLANOB(setravar): Sedemorarmaisde30minutosoutravar,podemos: 1. Interromper(Ctrl+C) 2. Processaroarquivograndeseparadamentecomoutrométod... [TRUNCADO]
      [6]:
        n: 07
        id: go2b::000305
        title: Legal Document Matrix Analysis - Claude.pdf
        section: page:9
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Legal Document Matrix Analysis - Claude.pdf
        source_sha256: 53714691749d482a8f32eb37e7c53ee58e269cab0f1b8ea39d3dd4dd80ba3b68
        snippet: print(f"SHA-256: {file_hash}") print(f"Size: {os.path.getsize(filename):,} bytes") return filename, file_hash def query(self, query_type: str, query_value: Any) -> Any: """Sistema de consulta rápida""... [TRUNCADO]
      [7]:
        n: 08
        id: go2b::005990
        title: artefatos.txt
        section: full
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/artefatos.txt
        source_sha256: 512384296e4082db815d850455b66db77e7117ca6b3a21b213faeb91cf8daca9
        snippet: 
      [8]:
        n: 09
        id: go2b::000300
        title: Legal Document Matrix Analysis - Claude.pdf
        section: page:7
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Legal Document Matrix Analysis - Claude.pdf
        source_sha256: 53714691749d482a8f32eb37e7c53ee58e269cab0f1b8ea39d3dd4dd80ba3b68
        snippet: damages": { "direct": { "ect_credit": 387055636.47, "pl_appropriation": 600000, "denied_savings": 18337.90, "judicial_blocks": 15000000, "labor_fines": 45000000, "subtotal": 447655636.47 }, "indirect"... [TRUNCADO]
      [9]:
        n: 10
        id: go2b::010474
        title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
        section: page:195
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
        source_sha256: 30c3db760ca2d0d412438669aecf03d6764faebeb9cb48bc71968b1645252424
        snippet: • NF12 -REPACTEMITIR: Item de Cobrança Valor Bruto Link Integrado -Memoriais NF01 -PENDPAGAMENTO R$ 18.553.608,25 NF0205 -FATPENDENTE(CAUTELAR) R$ 28.312.489,40 NF06 -HSDIVEDSR R$ 12.244.009,31 NF07 -... [TRUNCADO]
      [10]:
        n: 11
        id: go2b::007588
        title: artefatos.pdf
        section: page:394
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/artefatos.pdf
        source_sha256: 66bd9ec71221728dbbefa3c914d08d830617e2d33620521104b2258b7d6b6a07
        snippet: • NF12 -REPACTEMITIR: Item de Cobrança Valor Bruto Link Integrado -Memoriais NF01 -PENDPAGAMENTO R$ 18.553.608,25 NF0205 -FATPENDENTE(CAUTELAR) R$ 28.312.489,40 NF06 -HSDIVEDSR R$ 12.244.009,31 NF07 -... [TRUNCADO]
      [11]:
        n: 12
        id: go2b::003296
        title: todosfusao.pdf
        section: page:394
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.pdf
        source_sha256: bdd86800904c452cd3064be787b165ff128732d840e4031b62907c518b383a81
        snippet: • NF12 -REPACTEMITIR: Item de Cobrança Valor Bruto Link Integrado -Memoriais NF01 -PENDPAGAMENTO R$ 18.553.608,25 NF0205 -FATPENDENTE(CAUTELAR) R$ 28.312.489,40 NF06 -HSDIVEDSR R$ 12.244.009,31 NF07 -... [TRUNCADO]
      [12]:
        n: 13
        id: go2b::010817
        title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
        section: page:137
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
        source_sha256: a4705c43de3ee368172575ac27d9b19a02591ec556262646d7f169586cbde3e4
        snippet: Jardim da Silva, ONLOG; Sergio Eduardo Roda Junior, ONLOG; José Furian Filho, ONLOG/Sinerlog; José Carlos da Rocha Lima, ONLOG; Helder Braz Jardim da Silva, NOSS/ONLOG; Alessandro Esteves da Silva, Su... [TRUNCADO]
      [13]:
        n: 14
        id: go2b::007166
        title: artefatos.pdf
        section: page:190
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/artefatos.pdf
        source_sha256: 66bd9ec71221728dbbefa3c914d08d830617e2d33620521104b2258b7d6b6a07
        snippet: Jardim da Silva, ONLOG; Sergio Eduardo Roda Junior, ONLOG; José Furian Filho, ONLOG/Sinerlog; José Carlos da Rocha Lima, ONLOG; Helder Braz Jardim da Silva, NOSS/ONLOG; Alessandro Esteves da Silva, Su... [TRUNCADO]
      [14]:
        n: 15
        id: go2b::002874
        title: todosfusao.pdf
        section: page:190
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.pdf
        source_sha256: bdd86800904c452cd3064be787b165ff128732d840e4031b62907c518b383a81
        snippet: Jardim da Silva, ONLOG; Sergio Eduardo Roda Junior, ONLOG; José Furian Filho, ONLOG/Sinerlog; José Carlos da Rocha Lima, ONLOG; Helder Braz Jardim da Silva, NOSS/ONLOG; Alessandro Esteves da Silva, Su... [TRUNCADO]
      [15]:
        n: 16
        id: go2b::000070
        title: ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
        section: page:33
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseAlertas-FaltaAtuacaoPL-Ceo.pdf
        source_sha256: f0b272a16c5efdb509f03afc3465dd6ecf24c0c583ce696cc0a04ab7c3e68769
        snippet: 33 <pitney.operacoes07@chubb.com >; Chubb Expedição Brazil < expedicao.br@chubb.com > Assunto: RES: FATURA - BANCO ABC BRASIL - GOIAS BUSINESS @Sueto, Simone Y , Notei que já fizemos alguns pagamentos... [TRUNCADO]
      [16]:
        n: 17
        id: go2b::004246
        title: todosfusao.pdf
        section: page:850
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/memoriainstitucional/todosfusao.pdf
        source_sha256: bdd86800904c452cd3064be787b165ff128732d840e4031b62907c518b383a81
        snippet: 33 <pitney.operacoes07@chubb.com >; Chubb Expedição Brazil < expedicao.br@chubb.com > Assunto: RES: FATURA - BANCO ABC BRASIL - GOIAS BUSINESS @Sueto, Simone Y , Notei que já fizemos alguns pagamentos... [TRUNCADO]
      [17]:
        n: 18
        id: go2b::000302
        title: Legal Document Matrix Analysis - Claude.pdf
        section: page:8
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Legal Document Matrix Analysis - Claude.pdf
        source_sha256: 53714691749d482a8f32eb37e7c53ee58e269cab0f1b8ea39d3dd4dd80ba3b68
        snippet: }, "contractual_violations": { "query": "contract violations count", "answer": "6 clauses systematically violated" }, "impediment_proof": { "query": "impediment evidence", "answer": "Kinship + R$ 17M ... [TRUNCADO]
      [18]:
        n: 19
        id: go2b::009132
        title: documentosbaseconhecimento.pdf
        section: page:33
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/documentosbaseconhecimento.pdf
        source_sha256: 54118726f5790f80a5515c41add7834e2b1257a261434c30ab8f9a62dc6417d4
        snippet: 33 <pitney.operacoes07@chubb.com >; Chubb Expedição Brazil < expedicao.br@chubb.com > Assunto: RES: FATURA - BANCO ABC BRASIL - GOIAS BUSINESS @Sueto, Simone Y , Notei que já fizemos alguns pagamentos... [TRUNCADO]
      [19]:
        n: 20
        id: go2b::008181
        title: Projeto Knowledge Document Review - Claude.pdf
        section: page:15
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto Knowledge Document Review - Claude.pdf
        source_sha256: 1f801a952593ebae43efb1bb1dd40cf333d51fc908714925c52c070df85998f6
        snippet: O PROBLEMA IDENTIFICADO: Os resultados vazios indicam que: 1. Os caminhos dos diretórios estão incorretos 2. Ou os PDFs não estão nesses diretórios EXECUTE ESTE COMANDO PRIMEIRO para verificar: Execut... [TRUNCADO]
      [20]:
        n: 21
        id: go2b::007457
        title: artefatos.pdf
        section: page:334
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/artefatos.pdf
        source_sha256: 66bd9ec71221728dbbefa3c914d08d830617e2d33620521104b2258b7d6b6a07
        snippet: berativo – Edgard de Aguiar Cordeiro; Membro eleita do Conselho Deliberativo – Amanda Gomes Corcino; e Membro eleito do Conselho Deliberativo – Anézio Rodrigues; c.8) dos seguintes cidadãos, ocupantes... [TRUNCADO]
      [21]:
        n: 22
        id: go2b::006719
        title: chatsclaudeprojeto.pdf
        section: page:219
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/chatsclaudeprojeto.pdf
        source_sha256: ac73565b36e7cc8e195d0a1196dea8ea4ee6724902c959ce1c4ccca4008f7b81
        snippet: O PROBLEMA IDENTIFICADO: Os resultados vazios indicam que: 1. Os caminhos dos diretórios estão incorretos 2. Ou os PDFs não estão nesses diretórios EXECUTE ESTE COMANDO PRIMEIRO para verificar: Execut... [TRUNCADO]
      [22]:
        n: 23
        id: go2b::000169
        title: ContextoeHistoricoImp.pdf
        section: page:20
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ContextoeHistoricoImp.pdf
        source_sha256: 9d77128c18f635ed6370562c9a60d47da676820885167e61d83071d16d0076db
        snippet: 7L<# .=)58%698!#5LJJ "#9 !!%"$%!%"FG()*+H)$)?-@)(FG3)HA3.A*B+?$!!%"$%!%"56"778!J#55";%!%6$!! %!%<5<!775"!<6J#6!!"8 .=)%<68655LJ" .=)6866%8#66LJ9 <5% !!%7$%!%6FG()*+H)$)@H)C3.H20B3)FM(.F@3$!!%7$%!%656"... [TRUNCADO]
      [23]:
        n: 24
        id: go2b::009800
        title: documentosbaseconhecimento.pdf
        section: page:349
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/documentosbaseconhecimento.pdf
        source_sha256: 54118726f5790f80a5515c41add7834e2b1257a261434c30ab8f9a62dc6417d4
        snippet: 05/06/2025, 17:21Gerenciamento de conta - Registro.br As mensagens abaixo são referentes a erros que podem ocorrer no DS: FAIL - Erro/Falha no DNS - Ocorreu um erro na comunicação com o servidor DNS.•... [TRUNCADO]
      [24]:
        n: 25
        id: go2b::010343
        title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
        section: page:135
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
        source_sha256: 30c3db760ca2d0d412438669aecf03d6764faebeb9cb48bc71968b1645252424
        snippet: berativo – Edgard de Aguiar Cordeiro; Membro eleita do Conselho Deliberativo – Amanda Gomes Corcino; e Membro eleito do Conselho Deliberativo – Anézio Rodrigues; c.8) dos seguintes cidadãos, ocupantes... [TRUNCADO]
      [25]:
        n: 26
        id: go2b::000308
        title: Legal Document Matrix Analysis - Claude.pdf
        section: page:10
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Legal Document Matrix Analysis - Claude.pdf
        source_sha256: 53714691749d482a8f32eb37e7c53ee58e269cab0f1b8ea39d3dd4dd80ba3b68
        snippet: Este script Python gera: 1. JSON estruturado com toda base de conhecimento indexada 2. Sistema de consultas por data, ator, violação, valor 3. Motor de inferência para urgência e estratégias 4. Índice... [TRUNCADO]
      [26]:
        n: 27
        id: go2b::009626
        title: documentosbaseconhecimento.pdf
        section: page:240
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/documentosbaseconhecimento.pdf
        source_sha256: 54118726f5790f80a5515c41add7834e2b1257a261434c30ab8f9a62dc6417d4
        snippet: Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 – Brasília / DF Tels: +55 61 3303-1717/3303-3117 Willians Cristiano Marques, Melhor Envio; Tiago Vicente Alv... [TRUNCADO]
      [27]:
        n: 28
        id: go2b::011140
        title: MPF-JuntadaAutosECT-Completo-vs25082025.pdf
        section: page:49
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/MPF-JuntadaAutosECT-Completo-vs25082025.pdf
        source_sha256: 6d06824add65dd5fe5a51f6aab6ade27816ffed98d74d56acbb93e4432469eec
        snippet: Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 – Brasília / DF Tels: +55 61 3303-1717/3303-3117 Willians Cristiano Marques, Melhor Envio; Tiago Vicente Alv... [TRUNCADO]
      [28]:
        n: 29
        id: go2b::011250
        title: RelatorioTrocaDNS19052025.pdf
        section: page:13
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RelatorioTrocaDNS19052025.pdf
        source_sha256: ed05946c7324112e61528c6b8f7af9cfe982f77bb89b0eb63838fe8bed904a6b
        snippet: 05/06/2025, 17:21Gerenciamento de conta - Registro.br As mensagens abaixo são referentes a erros que podem ocorrer no DS: FAIL - Erro/Falha no DNS - Ocorreu um erro na comunicação com o servidor DNS.•... [TRUNCADO]
      [29]:
        n: 30
        id: go2b::011453
        title: ComunicacoeseAlertas-FaltaAtuaçaoPL-Jur.pdf
        section: page:3
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ComunicacoeseAlertas-FaltaAtuaçaoPL-Jur.pdf
        source_sha256: 8498f85865f92576ac0fc39456cf89bfa060aeb35d6abc38643634410160f3cf
        snippet: a - Goias Business Consultoria e Serviços Ltda - FLY RECUPERAÇÕES EMPRESARIAIS LTDA - BANCO BRADESCO S/A - - Caixa Econômica Federal - - Banco do Brasil S/A - - Banco ABC Brasil S.A. - - Itaú Unibanco... [TRUNCADO]
      [30]:
        n: 31
        id: go2b::010344
        title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
        section: page:136
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
        source_sha256: 30c3db760ca2d0d412438669aecf03d6764faebeb9cb48bc71968b1645252424
        snippet: SF/25122.07839-60 Assinado eletronicamente, por Sen. Flávio Bolsonaro Para verificar as assinaturas, acesse Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 ... [TRUNCADO]
      [31]:
        n: 32
        id: go2b::007458
        title: artefatos.pdf
        section: page:335
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/artefatos.pdf
        source_sha256: 66bd9ec71221728dbbefa3c914d08d830617e2d33620521104b2258b7d6b6a07
        snippet: SF/25122.07839-60 Assinado eletronicamente, por Sen. Flávio Bolsonaro Para verificar as assinaturas, acesse Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 ... [TRUNCADO]
      [32]:
        n: 33
        id: go2b::011684
        title: matriz_unificada_go2b_v7.json
        section: json
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/MatrizJson/matriz_unificada_go2b_v7.json
        source_sha256: 8b8e7aa7cdf19a9ab18a6208bb857e8f53540da66d745814ba1cbc8d6710477e
        snippet: 03]/id", "type_conflict": { "left_type": "str", "right_type": "str" }, "kept_richness": [ 1, 7 ] }, { "path": "events/[id=evt_003]/date", "type_conflict": { "left_type": "str", "right_type": "str" }, ... [TRUNCADO]
      [33]:
        n: 34
        id: go2b::006764
        title: chatsclaudeprojeto.pdf
        section: page:236
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/chatsclaudeprojeto.pdf
        source_sha256: ac73565b36e7cc8e195d0a1196dea8ea4ee6724902c959ce1c4ccca4008f7b81
        snippet: 1. VERIFIQUE A MEMÓRIA E CPU: Procure pelo processo Python - deve estar usando bastante memória (provavelmente 2-4 GB). 2. VERIFIQUE SE ESTÁ CRIANDO ARQUIVOS PARCIAIS: 3. ESTIMATIVA DE TEMPO: 450 MB c... [TRUNCADO]
      [34]:
        n: 35
        id: go2b::008226
        title: Projeto Knowledge Document Review - Claude.pdf
        section: page:32
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto Knowledge Document Review - Claude.pdf
        source_sha256: 1f801a952593ebae43efb1bb1dd40cf333d51fc908714925c52c070df85998f6
        snippet: 1. VERIFIQUE A MEMÓRIA E CPU: Procure pelo processo Python - deve estar usando bastante memória (provavelmente 2-4 GB). 2. VERIFIQUE SE ESTÁ CRIANDO ARQUIVOS PARCIAIS: 3. ESTIMATIVA DE TEMPO: 450 MB c... [TRUNCADO]
      [35]:
        n: 36
        id: go2b::006732
        title: chatsclaudeprojeto.pdf
        section: page:224
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/chatsclaudeprojeto.pdf
        source_sha256: ac73565b36e7cc8e195d0a1196dea8ea4ee6724902c959ce1c4ccca4008f7b81
        snippet: print(f" • Menções crime falimentar: {analyzer.stats['mencoes_crime']}") print(f" • Menções R$ 387 milhões: {analyzer.stats['mencoes_387mi']}") print(f" • Erros encontrados: {len(analyzer.errors)}") p... [TRUNCADO]
      [36]:
        n: 37
        id: go2b::008194
        title: Projeto Knowledge Document Review - Claude.pdf
        section: page:20
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto Knowledge Document Review - Claude.pdf
        source_sha256: 1f801a952593ebae43efb1bb1dd40cf333d51fc908714925c52c070df85998f6
        snippet: print(f" • Menções crime falimentar: {analyzer.stats['mencoes_crime']}") print(f" • Menções R$ 387 milhões: {analyzer.stats['mencoes_387mi']}") print(f" • Erros encontrados: {len(analyzer.errors)}") p... [TRUNCADO]
      [37]:
        n: 38
        id: go2b::006707
        title: chatsclaudeprojeto.pdf
        section: page:214
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/chatsclaudeprojeto.pdf
        source_sha256: ac73565b36e7cc8e195d0a1196dea8ea4ee6724902c959ce1c4ccca4008f7b81
        snippet: INSTRUÇÕES PARA USAR: 1. Instale as dependências: 2. Obtenha uma API key da Anthropic: Crie uma API key Substitua no script 3. Execute o script: 4. Traga os resultados para cá: O script gerará arquivo... [TRUNCADO]
      [38]:
        n: 39
        id: go2b::008169
        title: Projeto Knowledge Document Review - Claude.pdf
        section: page:10
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Projeto Knowledge Document Review - Claude.pdf
        source_sha256: 1f801a952593ebae43efb1bb1dd40cf333d51fc908714925c52c070df85998f6
        snippet: INSTRUÇÕES PARA USAR: 1. Instale as dependências: 2. Obtenha uma API key da Anthropic: Crie uma API key Substitua no script 3. Execute o script: 4. Traga os resultados para cá: O script gerará arquivo... [TRUNCADO]
      [39]:
        n: 40
        id: go2b::010361
        title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
        section: page:143
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs02.md - Bloco de notas.pdf
        source_sha256: 30c3db760ca2d0d412438669aecf03d6764faebeb9cb48bc71968b1645252424
        snippet: presálias”, segue a denúncia. MAIS LIDASEm 11 de junho de 2023, por exemplo, há uma mensagem do dirigente pedindoemprego para uma mulher. “Atualmente ela é minha companheira e, portanto, nãopoderia la... [TRUNCADO]
      [40]:
        n: 41
        id: go2b::000131
        title: ContextoeHistoricoImp.pdf
        section: page:7
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/ContextoeHistoricoImp.pdf
        source_sha256: 9d77128c18f635ed6370562c9a60d47da676820885167e61d83071d16d0076db
        snippet: para o momento, mas saiba que sobrevivo hoje de emprés6mos de familiares e venda de objetos par6culares (Até vídeo game do meu filho vendi). Adiciono situações especificas como a interrupção de tratamen... [TRUNCADO]
      [41]:
        n: 42
        id: go2b::000380
        title: GitHub Raw Files Analysis - Claude.pdf
        section: page:23
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/GitHub Raw Files Analysis - Claude.pdf
        source_sha256: dbdbb765bb194d677e0a05b4ffcc075c0828e0b7b47744de0a836bff67e620fd
        snippet: Venda de todos os bens pessoais Dependência de caridade familiar 17.2. IMPACTO NOS 6.000 TRABALHADORES DADOS SOCIAIS CRÍTICOS: 6.000 famílias sem renda Aproximadamente 24.000 pessoas afetadas 85% dos ... [TRUNCADO]
      [42]:
        n: 43
        id: go2b::011138
        title: MPF-JuntadaAutosECT-Completo-vs25082025.pdf
        section: page:48
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/MPF-JuntadaAutosECT-Completo-vs25082025.pdf
        source_sha256: 6d06824add65dd5fe5a51f6aab6ade27816ffed98d74d56acbb93e4432469eec
        snippet: Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 – Brasília / DF Tels: +55 61 3303-1717/3303-3117 c.6) dos seguintes cidadãos, ocupantes e ex-ocupantes de ca... [TRUNCADO]
      [43]:
        n: 44
        id: go2b::011136
        title: MPF-JuntadaAutosECT-Completo-vs25082025.pdf
        section: page:47
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/MPF-JuntadaAutosECT-Completo-vs25082025.pdf
        source_sha256: 6d06824add65dd5fe5a51f6aab6ade27816ffed98d74d56acbb93e4432469eec
        snippet: Senador FLÁVIO BOLSONARO – PL/RJ Senado Federal - Anexo I – 17o ANDAR - Torre CEP 70165-900 – Brasília / DF Tels: +55 61 3303-1717/3303-3117 b.3) Ministra da Gestão e Inovação em Serviços Públicos; c)... [TRUNCADO]
      [44]:
        n: 45
        id: go2b::010834
        title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
        section: page:144
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
        source_sha256: a4705c43de3ee368172575ac27d9b19a02591ec556262646d7f169586cbde3e4
        snippet: nstrado que essa postura não visava resolver efetivamente ainadimplência da ECT, mas sim criar um ambiente de confiança artificial parainduzir a GO2B a contratar terceirizados indicados por interesses... [TRUNCADO]
      [45]:
        n: 46
        id: go2b::010816
        title: fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
        section: page:136
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/Artefatos/fusaointegradaGo2bRecupJudicialGPTcomEnviodocsvs01.md - Bloco de notas.pdf
        source_sha256: a4705c43de3ee368172575ac27d9b19a02591ec556262646d7f169586cbde3e4
        snippet: s e funções no Postalis: presidente, Camilo Fernandes dos Santos; ex-presidente do Postalis, Antônio Carlos Conquista; ex-presidente do Postalis,; Membro indicado do Conselho Deliberativo – Hudson Alv... [TRUNCADO]
      [46]:
        n: 47
        id: go2b::008423
        title: Matrix Integration and Knowledge Maximization - Claude.pdf
        section: page:11
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/chatsclaude/Matrix Integration and Knowledge Maximization - Claude.pdf
        source_sha256: 209d5ffe6e9f5cc851e29645c7b9884b0365dc05a44d92cf2a475b2a470843fb
        snippet: "total_characters_processed": 15762027, "confidence_overall": 0.99, "consistency_checks": [ "timezone_normalized: America/Sao_Paulo", "ids_crosslinked: events<->evidence<->violations<->remedies", "dup... [TRUNCADO]
      [47]:
        n: 48
        id: go2b::011238
        title: RelatorioTrocaDNS19052025.pdf
        section: page:7
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RelatorioTrocaDNS19052025.pdf
        source_sha256: ed05946c7324112e61528c6b8f7af9cfe982f77bb89b0eb63838fe8bed904a6b
        snippet: 05/06/2025, 17:21Gerenciamento de conta - Registro.br 3. Token O que é o token? Um segundo fator de segurança para acesso ao nosso sistema, conhecido também como "Verificação em Duas Etapas". Seu uso ... [TRUNCADO]
      [48]:
        n: 49
        id: go2b::011248
        title: RelatorioTrocaDNS19052025.pdf
        section: page:12
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RelatorioTrocaDNS19052025.pdf
        source_sha256: ed05946c7324112e61528c6b8f7af9cfe982f77bb89b0eb63838fe8bed904a6b
        snippet: 05/06/2025, 17:21Gerenciamento de conta - Registro.br CCU Unicamp(Português) LDP DNS-HOWTO Literatura P. Albitz, C. Liu, "DNS and BIND, 4th. edition", OReilly & Associates, Inc. - ISBN: 0596001584 Qua... [TRUNCADO]
      [49]:
        n: 50
        id: go2b::011252
        title: RelatorioTrocaDNS19052025.pdf
        section: page:14
        source_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/DocsUsadosOrientacao/SeparacaoTxt/documentosconhecimento/RelatorioTrocaDNS19052025.pdf
        source_sha256: ed05946c7324112e61528c6b8f7af9cfe982f77bb89b0eb63838fe8bed904a6b
        snippet: 05/06/2025, 17:21Gerenciamento de conta - Registro.br Como um dos contatos mencionados acima, acesse o sistema com seu Usuário e senha e selecione o nome do domínio. Na tela seguinte, você terá acesso... [TRUNCADO]
      [... +170 itens omitidos]
    messages:
      [0]:
        role: system
        content: Você é um assistente jurídico/técnico focado no dossiê GO2B. Use EXCLUSIVAMENTE as evidências abaixo; cite o item [01], [02] etc. Se faltar base, escreva literalmente: 'FALTA EVIDÊNCIA PARA: ...'. Estru... [TRUNCADO]
      [1]:
        role: system
        content: POLÍTICA: Todo fato deve citar [no do item]. Onde faltar, escrever: 'FALTA EVIDÊNCIA PARA: ...'.
      [2]:
        role: user
        content: Use apenas as evidências listadas abaixo, citando [no do item].
  preview: {'created_at': '2025-08-26 09:22:58', 'system_prompt': "Você é um assistente jurídico/técnico focado no dossiê GO2B. Use EXCLUSIVAMENTE as evidências abaixo; cite o item [01], [02] etc. Se faltar base... [TRUNCADO]
  error: None
analise_claude:
  documento: MEGA_CONTEXT.json
  analise_expandida: True
  total_chunks: 4
  chunks_com_sucesso: 4
  analise_ia_completa:
    resumo_documento: Documento MEGA_CONTEXT.json apresenta matriz de análise do caso GO2B, contendo métricas, achados principais e protocolo de comunicações híbrido. Inclui anexos com evidências de degradação documental, ... [TRUNCADO]
    contexto_caso: Este é um documento central que estrutura a análise técnica do caso, estabelecendo protocolos e consolidando evidências sobre a apropriação de valores pela PL e violações processuais sistemáticas.
    informacoes_chave:
      [0]:
        78 documentos analisados no total
      [1]:
        20 violações identificadas
      [2]:
        32 provas catalogadas
      [3]:
        Degradação progressiva da qualidade das peças da PL
      [4]:
        GO2B sem representação desde 19/05/2025
      [5]:
        Omissão/degradação do crédito ECT nas peças principais
      [6]:
        Autofalência proposta sem documentos obrigatórios
      [7]:
        Indícios criminais identificados
      [8]:
        Plano de comunicações híbrido estabelecido
      [9]:
        Checklist de verificação com 6 pontos críticos
      [10]:
        R$ 387.055.636,47 em crédito ECT identificado
      [11]:
        R$ 600.000 em apropriação pela PL documentada
      [12]:
        Crédito ECT confirmado de R$ 387.055.636,47
      [13]:
        CMZ realizou pagamento do acordo conforme evidências
      [14]:
        PL apropriou-se indevidamente de valores
      [15]:
        Existência de 6.000+ colaboradores afetados
      [16]:
        CEO vendeu bens pessoais incluindo videogame do filho autista
      [17]:
        52 documentos processados com 15.762.027 caracteres
      [18]:
        Proposta GO2B de comunicação digital foi ignorada
      [19]:
        Custos de R$ 18.000 em cartas físicas questionados
      [20]:
        Alteração DNS realizada em 19/05/2025 às 13h30
      [21]:
        Novos servidores: ns1.provider2.com.br e ns2.provider2.com.br
      [22]:
        Período de propagação: 13h30-16h00
      [23]:
        Emails ficaram tecnicamente inviabilizados neste intervalo
      [24]:
        Sistema retorna mensagens como não enviadas durante propagação
      [25]:
        Mudança seguiu política oficial do Registro.BR
      [26]:
        Troca DNS ocorreu em 19/05/2025 entre 13:30-16:00 [166]
      [27]:
        Às 14:00 sistema tinha apenas 15% de disponibilidade [166]
      [28]:
        Taxa de falha superior a 85% nas mensagens [166]
      [29]:
        Certificação técnica com fé pública pelo Registro.br [166]
      [30]:
        GO2B está sem representação desde 19/05/2025 [166]
      [31]:
        Apropriação de R$ 600.000,00 pela PL confirmada via extratos CMZ [172]
      [32]:
        Crédito ECT de R$ 387.055.636,47 não recebido [172]
      [33]:
        Bloqueios judiciais de R$ 15.000.000/mês [172]
      [34]:
        Multas trabalhistas totalizam R$ 45.000.000,00 [172]
      [35]:
        6.000 processos trabalhistas em andamento [172]
    relevancia_juridica: alta
    recomendacoes:
      [0]:
        Implementar plano de comunicações híbrido conforme protocolo
      [1]:
        Peticionar listagem completa de credores/processos
      [2]:
        Consolidar comprovantes de intimação digital
      [3]:
        Preservar cadeia de custódia das evidências
      [4]:
        Formalizar denúncia sobre omissão do crédito ECT
      [5]:
        Protocolar pedido urgente de destituição do AJ
      [6]:
        Denunciar PL ao MPF por apropriação indébita
      [7]:
        Requerer suspensão processual por prejudicialidade
      [8]:
        Solicitar perícia nos documentos do caso CMZ
      [9]:
        Apresentar plano alternativo de comunicação
      [10]:
        Autenticar documento em cartório
      [11]:
        Requerer perícia técnica nos servidores
      [12]:
        Oficiar Registro.BR para confirmação
      [13]:
        Usar como prova central da nulidade da renúncia
      [14]:
        Solicitar logs dos servidores de email
      [15]:
        Protocolar exceção de impedimento imediatamente [173]
      [16]:
        Pressionar Corregedoria para afastamento [173]
      [17]:
        Mobilizar opinião pública via imprensa [173]
      [18]:
        Proteger patrimônio via medidas cautelares [173]
      [19]:
        Peticionar ao Senado sobre convocação CEO [173]
  irregularidades:
    apropriacao_cmz:
      detectada: True
      evidencias:
        [0]:
          Fluxo financeiro documentado em anexo_fluxo_dinheiro.png
        [1]:
          Valores ECT→AJ→PL/GO2B/Terceiros mapeados
        [2]:
          Documentos comprovam pagamento por CMZ
        [3]:
          Valores não repassados à GO2B
        [4]:
          Retenção indevida confirmada
        [5]:
          Extratos CMZ comprovam apropriação [172]
        [6]:
          Valor de R$ 600.000,00 confirmado [172]
      detalhes:

      valores:
        [0]:
          R$ 600.000 apropriados pela PL
        [1]:
          Valor não especificado nos trechos
        [2]:
          R$ 600.000,00
      responsaveis:
        [0]:
          PL
        [1]:
          AJ
        [2]:
          PL Consultoria
        [3]:
          PL Consultoria
    renuncia_irregular:
      detectada: True
      evidencias:
        [0]:
          Marco 19/05/2025 (DNS/renúncia)
        [1]:
          GO2B sem representação desde 19/05/2025
        [2]:
          Abandono sem renúncia formal
        [3]:
          Mudança DNS em 19/05/2025 13h30
        [4]:
          Período de propagação até 16h00
        [5]:
          Impossibilidade técnica de recebimento de emails
        [6]:
          Certificado técnico Registro.br [166]
        [7]:
          15% disponibilidade às 14:00 [166]
        [8]:
          85% taxa de falha em emails [166]
      detalhes:

      timeline:
        [0]:
          19/05/2025 - Renúncia
        [1]:
          28/05/2025 - Ato do AJ
        [2]:
          19/05/2025 - Início do período sem representação
        [3]:
          13h30 - Alteração DNS iniciada
        [4]:
          13h30-16h00 - Período de propagação
        [5]:
          16h00 - Nova configuração ativa
        [6]:
          13:30 - Início propagação DNS [166]
        [7]:
          14:00 - Alegada renúncia (15% disponibilidade) [166]
        [8]:
          16:00 - Fim propagação DNS [166]
    impedimento_judicial:
      detectada: True
      evidencias:
        [0]:
          MPF 20-22/08/2025 (juntada/despacho/envio PF)
        [1]:
          Relação AJ-Juiz documentada
        [2]:
          Evidências de conflito de interesses
        [3]:
          Rede de relacionamentos documentada [176]
        [4]:
          Conexão familiar comprovada [176]
      detalhes:

      cadeia_interesse:
        [0]:
          AJ
        [1]:
          Juiz (irmão)
        [2]:
          Juiz
        [3]:
          AJ
        [4]:
          PL
        [5]:
          Juiz → Irmão → Parceiro → Esposa → AJ [176]
        [6]:
          Negócios de R$ 17 milhões identificados [176]
    negligencia_profissional:
      detectada: True
      evidencias:

      detalhes:

      padroes:
        [0]:
          Degradação documental sistemática
        [1]:
          Omissão de crédito ECT
        [2]:
          Recusa de soluções econômicas
        [3]:
          Omissão em defesas
        [4]:
          Falta de diligência
        [5]:
          Tentativa de forçar renúncia em período de instabilidade técnica
        [6]:
          Não verificação do recebimento efetivo da comunicação
        [7]:
          Degradação progressiva das petições [177]
        [8]:
          Omissão sistemática sobre crédito ECT [177]
      exemplos:
        [0]:
          Autofalência sem documentos obrigatórios
        [1]:
          Recusa do plano digital de comunicações
        [2]:
          Insistência em gastos desnecessários
        [3]:
          Ausência de defesa adequada
        [4]:
          Envio de email em período de propagação DNS
        [5]:
          Não menção ao crédito de R$ 387 milhões [177]
        [6]:
          Abandono processual por 180 dias [177]
    custas_cartas:
      detectada: True
      evidencias:

      detalhes:

  evidencias_documentais:
    [0]:
      anexo_degradacao.png
    [1]:
      anexo_fluxo_dinheiro.png
    [2]:
      anexo_tabela_violacoes.csv
    [3]:
      52 documentos processados
    [4]:
      15.762.027 caracteres analisados
    [5]:
      Petição de 09/06/2025
    [6]:
      Documentos do caso CMZ
    [7]:
      E-mails e comunicações
    [8]:
      Registro de alteração DNS - 19/05/2025 13h30
    [9]:
      Configuração novos servidores DNS
    [10]:
      Política de propagação Registro.BR
    [11]:
      Certificado DNS Registro.br [166]
    [12]:
      Extratos bancários CMZ [172]
    [13]:
      Relatório técnico propagação DNS [166]
    [14]:
      Documentação impedimento judicial [176]
  valores_financeiros:
    [0]:
      R$ 387.055.636,47 - crédito ECT
    [1]:
      R$ 600.000 - apropriação PL
    [2]:
      R$ 387.055.636,47 - Crédito ECT
    [3]:
      R$ 18.000 - Custo cartas físicas
    [4]:
      R$ 100.000 - Custo evitado proposta digital
    [5]:
      R$ 387.055.636,47 - Crédito ECT [172]
    [6]:
      R$ 600.000,00 - Apropriação PL [172]
    [7]:
      R$ 15.000.000/mês - Bloqueios [172]
    [8]:
      R$ 45.000.000,00 - Multas trabalhistas [172]
    [9]:
      R$ 18.337,90/mês - Economia negada [172]
  datas_relevantes:
    [0]:
      19/05/2025 - Renúncia/DNS
    [1]:
      28/05/2025 - Ato AJ
    [2]:
      20-22/08/2025 - Ações MPF
    [3]:
      19/05/2025 - Início período sem representação
    [4]:
      09/06/2025 - Petição crucial
    [5]:
      28/05/2025 - Manifestação AJ contestada
    [6]:
      19/05/2025 13h30 - Alteração DNS
    [7]:
      19/05/2025 16h00 - Conclusão propagação
    [8]:
      19/05/2025 13:30-16:00 - Troca DNS [166]
    [9]:
      19/05/2025 14:00 - Alegada renúncia [166]
    [10]:
      26-30/08/2025 - Cronograma ações emergenciais [173]
  pessoas_mencionadas:
    [0]:
      Sen. Flávio Bolsonaro
    [1]:
      Adriano Hamu
    [2]:
      Irmão do juiz (AJ)
    [3]:
      Adriano Hamu - CEO GO2B
    [4]:
      Dagoberto Mello Lima - PL
    [5]:
      Livia Rebeca Chaves Figueiredo - Nova advogada
    [6]:
      Frederico Neves - Diretor Registro.br [166]
    [7]:
      Adriano Hamu - CEO GO2B [166]
    [8]:
      Quintino Fleury - AJ [176]
    [9]:
      Marcello Perino - Juiz [176]
  violacoes_legais:
    [0]:
      Apropriação indébita
    [1]:
      Violação do dever de lealdade processual
    [2]:
      Impedimento judicial não declarado
    [3]:
      Cerceamento de defesa
    [4]:
      Art. 168 CP - Apropriação indébita
    [5]:
      Art. 355 CP - Patrocínio infiel
    [6]:
      Art. 47 Lei 11.101/05 - Princípios RJ
    [7]:
      Art. 22 Lei 11.101/05 - Deveres AJ
    [8]:
      Art. 112 CPC - Renúncia sem comunicação válida
    [9]:
      Art. 5o §3o Lei 8.906/94 - Violação Estatuto OAB
    [10]:
      Art. 144 CPC - Impedimento judicial [176]
    [11]:
      Art. 168 CP - Apropriação indébita [176]
    [12]:
      Art. 355 CP - Patrocínio infiel [176]
    [13]:
      Lei 12.965/2014 - Marco Civil Internet [166]
  estrategias:

  nexo_causal:
    elementos:
      [0]:
        Renúncia irregular
      [1]:
        Apropriação de valores
      [2]:
        Impedimento judicial
      [3]:
        Degradação documental
      [4]:
        Apropriação de valores CMZ
      [5]:
        Abandono processual
      [6]:
        Recusa soluções econômicas
      [7]:
        Prejuízos à recuperação
      [8]:
        Alteração DNS
      [9]:
        Período de propagação
      [10]:
        Impossibilidade técnica
      [11]:
        Renúncia inválida
      [12]:
        Troca DNS intencional
      [13]:
        Renúncia em momento crítico
      [14]:
        Apropriação valores CMZ
      [15]:
        Impedimento judicial
    conexoes:
      [0]:
        Renúncia → Cerceamento defesa
      [1]:
        Impedimento → Decisões favoráveis
      [2]:
        Apropriação → Dano patrimonial
      [3]:
        Apropriação → Crise financeira
      [4]:
        Abandono → Prejuízo defesa
      [5]:
        Recusa digital → Custos desnecessários
      [6]:
        Alteração DNS causou período de instabilidade
      [7]:
        Instabilidade impossibilitou recebimento de emails
      [8]:
        Impossibilidade técnica invalida suposta renúncia
      [9]:
        DNS trocado para criar impossibilidade técnica
      [10]:
        Renúncia alegada no pior momento (15% disponibilidade)
      [11]:
        Apropriação facilitada pela ausência de representação
      [12]:
        Impedimento viabilizou toda a operação
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
FIM DOCUMENTO: analysis_MEGA_CONTEXT.json
REFERÊNCIA: doc46-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: analysis_MEGA_CONTEXT_20250826_203959.json
REFERÊNCIA: doc46-referencia
PROCESSADO EM: 04/09/2025 15:08:12
HASH ORIGINAL: f12c89ac6e5088dd7851f6cbd99bf6bd6043fa3259a241e6ff036d5a445e5a77
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
arquivo: MEGA_CONTEXT.json
descricao: Mega contexto JSON
estrutura:
  created_at: str
  system_prompt: str
  key_numbers:
    num_docs: int
    violacoes: int
    provas: int
  matrix_findings:
    [0]:
      str
  hybrid_comms: str
  proto_mestre_v2: str
  annexes_digest:
    [0]:
      name: ...
      path: ...
      size_bytes: ...
      mtime: ...
      sha256: ...
      description: ...
  evidence:
    [0]:
      n: ...
      id: ...
      title: ...
      section: ...
      source_path: ...
      source_sha256: ...
      snippet: ...
  messages:
    [0]:
      role: ...
      content: ...
estatisticas:
  tamanho: 430777
  chaves_principais:
    [0]:
      created_at
    [1]:
      system_prompt
    [2]:
      key_numbers
    [3]:
      matrix_findings
    [4]:
      hybrid_comms
    [5]:
      proto_mestre_v2
    [6]:
      annexes_digest
    [7]:
      evidence
    [8]:
      messages
  profundidade: 6

================================================================================
FIM DOCUMENTO: analysis_MEGA_CONTEXT_20250826_203959.json
REFERÊNCIA: doc46-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: reconciliado_MEGA_CONTEXT.json
REFERÊNCIA: doc46-referencia
PROCESSADO EM: 04/09/2025 15:08:12
HASH ORIGINAL: ae3bfdf5763ee0bc020c565203fec79bcda07e966827cfe547dbb4d431294cb1
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
arquivo: MEGA_CONTEXT.json
descricao: Mega contexto JSON
estrutura:
  created_at: str
  system_prompt: str
  key_numbers:
    num_docs: int
    violacoes: int
    provas: int
  matrix_findings:
    [0]:
      str
  hybrid_comms: str
  proto_mestre_v2: str
  annexes_digest:
    [0]:
      name: ...
      path: ...
      size_bytes: ...
      mtime: ...
      sha256: ...
      description: ...
  evidence:
    [0]:
      n: ...
      id: ...
      title: ...
      section: ...
      source_path: ...
      source_sha256: ...
      snippet: ...
  messages:
    [0]:
      role: ...
      content: ...
estatisticas:
  tamanho: 430777
  chaves_principais:
    [0]:
      created_at
    [1]:
      system_prompt
    [2]:
      key_numbers
    [3]:
      matrix_findings
    [4]:
      hybrid_comms
    [5]:
      proto_mestre_v2
    [6]:
      annexes_digest
    [7]:
      evidence
    [8]:
      messages
  profundidade: 6
metadata:
  reconciliado: True
  timestamp_reconciliacao: 2025-09-01T13:10:18.722510
  verdades_aplicadas:
    chunks: 758
    confidence: 0.85
    valores:
      apropriacao_cmz: 600000.0
      divida_ect: 387055636.47
      custas_cartas: 18000.0
      impedimento_interesse: 17000000.0
      prejuizo_total: 782655636.47
reconciliation_insights:
  paradoxos_encontrados:
    [0]:
      O arquivo indica 'reconciliado: true' mas pode precisar de nova reconciliação com as verdades estabelecidas
    [1]:
      Timestamp de reconciliação é futuro (2025-09-01)
    [2]:
      Valor total de prejuízo (782.655.636,47) parece desproporcional aos outros valores
  correcoes_aplicadas:
    [0]:
      Confirmado número de chunks: 758
    [1]:
      Confidence ajustado para >0.85
    [2]:
      Valor de apropriação fixado em R$ 600.000,00
    [3]:
      Status da GO2B confirmado como VÍTIMA
    [4]:
      Status da PL confirmado como APROPRIADORA
    [5]:
      Status do CMZ confirmado como PAGADOR (15/12/2023)
  informacoes_uteis:
    [0]:
      Estrutura bem definida com evidências e anexos catalogados
    [1]:
      Presença de matriz de descobertas (matrix_findings)
    [2]:
      Sistema de comunicações híbridas documentado
    [3]:
      Protocolo mestre v2 incluído
    [4]:
      Valores específicos documentados para diversos itens financeiros
  evidencias_preservadas:
    [0]:
      Estrutura de evidence[] mantida intacta
    [1]:
      Digest de anexos preservado
    [2]:
      Hash SHA256 dos documentos fonte mantido
    [3]:
      Histórico de mensagens preservado
  recomendacoes:
    [0]:
      Atualizar timestamp de reconciliação para data atual
    [1]:
      Revisar cálculo do prejuízo total
    [2]:
      Adicionar campo específico para data de pagamento do CMZ
    [3]:
      Incluir flags explícitos para status das partes (VÍTIMA/APROPRIADORA)
    [4]:
      Documentar fonte da confidence >0.85

================================================================================
FIM DOCUMENTO: reconciliado_MEGA_CONTEXT.json
REFERÊNCIA: doc46-referencia
INTEGRIDADE: VERIFICADA
================================================================================

