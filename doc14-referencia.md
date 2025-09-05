# Documentos Referência para construção do doc14

**Nome In Natura:** doc14: deep_memory.db

**Data de Processamento:** 04/09/2025 15:08:05

**Processo RJ:** 1039604-94.2023.8.26.0405

**Inquérito MPF:** 1.16.000.001860/2025-10

**Cadeia de Custódia:** MANTIDA (Hashes SHA-256 registrados)

**Audit Log:** MEGA_AUDIT_20250904_150743.log

---

## Temática do Documento

O **doc14** trata do tema: **Memória profunda e bases de conhecimento persistentes**

Os documentos abaixo são utilizados como **referência para extração desta temática específica**, não para uso integral. A referência pode conter múltiplos temas e complexidades, podendo apresentar duplicidades que serão tratadas nas fases posteriores.

## Controles de Segurança e Auditoria

- **Backup de Segurança:** Criado antes do processamento
- **Hashes de Integridade:** Calculados para todos os arquivos
- **Log de Auditoria:** Todas as operações registradas
- **Normalização UTF-8:** Aplicada preservando conteúdo original
- **Classificação LGPD:** Documentos classificados por sensibilidade

---

## Arquivos/Documentos Utilizados como Referência

1. `analysis_deep_memory.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `eaa87f088a9315c5eaa22140bf9a2a06ccb4928a040efc964e6402339708ece0`
   - Sensibilidade: ALTA_SENSIBILIDADE

2. `reconciliado_deep_memory.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `283dd14063455394c269c214cb8d7e7d2a00a3f01b6ebd4447e4c139b639c837`
   - Sensibilidade: ALTA_SENSIBILIDADE

3. `analysis_deep_memory_20250826_204000.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `af18ef4af374d9540c7f26a5673e1d086a4c7de68308161c9d4c23fb86f54c2e`
   - Sensibilidade: ALTA_SENSIBILIDADE

4. `deep_memory.db`
   - Tipo: SQLite - Banco de dados
   - Hash SHA-256: `dec31575339159463df5675c9136d5e4c8e6ce5d831e633b268b656c43af29bb`
   - Sensibilidade: ALTA_SENSIBILIDADE

---

\newpage

================================================================================
DOCUMENTO: analysis_deep_memory.json
REFERÊNCIA: doc14-referencia
PROCESSADO EM: 04/09/2025 15:08:05
HASH ORIGINAL: eaa87f088a9315c5eaa22140bf9a2a06ccb4928a040efc964e6402339708ece0
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
  file: deep_memory.db
  path: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/go2b_deep_memory/deep_memory.db
  timestamp: 2025-09-01T16:38:11.757159
  size: 94208
  type: database
  descricao: 
  is_critical: False
  preservacao: 100% conteudo mantido
content_extraction:
  success: True
  full_content:
    memory_nodes:
      columns:
        [0]:
          node_id
        [1]:
          node_type
        [2]:
          content
        [3]:
          embeddings
        [4]:
          metadata
        [5]:
          created_at
      column_types:
        node_id: TEXT
        node_type: TEXT
        content: TEXT
        embeddings: TEXT
        metadata: TEXT
        created_at: TIMESTAMP
      record_count: 29
      sample_data:
        [0]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [3]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [4]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [5]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [1]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [3]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [4]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [5]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [2]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [3]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [4]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [5]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [3]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [3]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [4]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [5]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [4]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [3]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [4]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [5]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
    memory_edges:
      columns:
        [0]:
          edge_id
        [1]:
          source_node
        [2]:
          target_node
        [3]:
          edge_type
        [4]:
          weight
        [5]:
          metadata
      column_types:
        edge_id: TEXT
        source_node: TEXT
        target_node: TEXT
        edge_type: TEXT
        weight: REAL
        metadata: TEXT
      record_count: 0
      sample_data: None
    temporal_events:
      columns:
        [0]:
          event_id
        [1]:
          event_date
        [2]:
          event_description
        [3]:
          actors
        [4]:
          evidence_refs
        [5]:
          importance
        [6]:
          metadata
      column_types:
        event_id: TEXT
        event_date: TEXT
        event_description: TEXT
        actors: TEXT
        evidence_refs: TEXT
        importance: INTEGER
        metadata: TEXT
      record_count: 0
      sample_data: None
  preview: {'memory_nodes': {'columns': ['node_id', 'node_type', 'content', 'embeddings', 'metadata', 'created_at'], 'column_types': {'node_id': 'TEXT', 'node_type': 'TEXT', 'content': 'TEXT', 'embeddings': 'TEX... [TRUNCADO]
  error: None
analise_claude:

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
FIM DOCUMENTO: analysis_deep_memory.json
REFERÊNCIA: doc14-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: reconciliado_deep_memory.json
REFERÊNCIA: doc14-referencia
PROCESSADO EM: 04/09/2025 15:08:05
HASH ORIGINAL: 283dd14063455394c269c214cb8d7e7d2a00a3f01b6ebd4447e4c139b639c837
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 7 chaves
Chaves principais:
  - tipo: str
  - arquivo: str
  - tabelas: list
  - estrutura: dict
  - descricao: str
  - metadata: dict
  - reconciliation_insights: dict

=== CONTEÚDO JSON ===
tipo: database
arquivo: deep_memory.db
tabelas:
  [0]:
    memory_nodes
  [1]:
    memory_edges
  [2]:
    temporal_events
estrutura:
  memory_nodes:
    [0]:
      [0]:
        0
      [1]:
        node_id
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        1
    [1]:
      [0]:
        1
      [1]:
        node_type
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        content
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [3]:
      [0]:
        3
      [1]:
        embeddings
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [4]:
      [0]:
        4
      [1]:
        metadata
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [5]:
      [0]:
        5
      [1]:
        created_at
      [2]:
        TIMESTAMP
      [3]:
        0
      [4]:
        CURRENT_TIMESTAMP
      [5]:
        0
  memory_edges:
    [0]:
      [0]:
        0
      [1]:
        edge_id
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        1
    [1]:
      [0]:
        1
      [1]:
        source_node
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        target_node
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [3]:
      [0]:
        3
      [1]:
        edge_type
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [4]:
      [0]:
        4
      [1]:
        weight
      [2]:
        REAL
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [5]:
      [0]:
        5
      [1]:
        metadata
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  temporal_events:
    [0]:
      [0]:
        0
      [1]:
        event_id
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        1
    [1]:
      [0]:
        1
      [1]:
        event_date
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        event_description
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [3]:
      [0]:
        3
      [1]:
        actors
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [4]:
      [0]:
        4
      [1]:
        evidence_refs
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [5]:
      [0]:
        5
      [1]:
        importance
      [2]:
        INTEGER
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [6]:
      [0]:
        6
      [1]:
        metadata
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
descricao: Deep memory database
metadata:
  reconciliado_v9: True
  timestamp_reconciliacao: 2025-09-01T17:23:10.614417
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
FIM DOCUMENTO: reconciliado_deep_memory.json
REFERÊNCIA: doc14-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: analysis_deep_memory_20250826_204000.json
REFERÊNCIA: doc14-referencia
PROCESSADO EM: 04/09/2025 15:08:05
HASH ORIGINAL: af18ef4af374d9540c7f26a5673e1d086a4c7de68308161c9d4c23fb86f54c2e
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 5 chaves
Chaves principais:
  - tipo: str
  - arquivo: str
  - tabelas: list
  - estrutura: dict
  - descricao: str

=== CONTEÚDO JSON ===
tipo: database
arquivo: deep_memory.db
tabelas:
  [0]:
    memory_nodes
  [1]:
    memory_edges
  [2]:
    temporal_events
estrutura:
  memory_nodes:
    [0]:
      [0]:
        0
      [1]:
        node_id
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        1
    [1]:
      [0]:
        1
      [1]:
        node_type
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        content
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [3]:
      [0]:
        3
      [1]:
        embeddings
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [4]:
      [0]:
        4
      [1]:
        metadata
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [5]:
      [0]:
        5
      [1]:
        created_at
      [2]:
        TIMESTAMP
      [3]:
        0
      [4]:
        CURRENT_TIMESTAMP
      [5]:
        0
  memory_edges:
    [0]:
      [0]:
        0
      [1]:
        edge_id
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        1
    [1]:
      [0]:
        1
      [1]:
        source_node
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        target_node
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [3]:
      [0]:
        3
      [1]:
        edge_type
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [4]:
      [0]:
        4
      [1]:
        weight
      [2]:
        REAL
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [5]:
      [0]:
        5
      [1]:
        metadata
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  temporal_events:
    [0]:
      [0]:
        0
      [1]:
        event_id
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        1
    [1]:
      [0]:
        1
      [1]:
        event_date
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        event_description
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [3]:
      [0]:
        3
      [1]:
        actors
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [4]:
      [0]:
        4
      [1]:
        evidence_refs
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [5]:
      [0]:
        5
      [1]:
        importance
      [2]:
        INTEGER
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [6]:
      [0]:
        6
      [1]:
        metadata
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
descricao: Deep memory database

================================================================================
FIM DOCUMENTO: analysis_deep_memory_20250826_204000.json
REFERÊNCIA: doc14-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: deep_memory.db
REFERÊNCIA: doc14-referencia
PROCESSADO EM: 04/09/2025 15:08:05
HASH ORIGINAL: dec31575339159463df5675c9136d5e4c8e6ce5d831e633b268b656c43af29bb
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE BANCO DE DADOS SQLITE ===
Arquivo: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/Bak-ExclusaoPossivelExtracao70jsons/checagem02/doc14/deep_memory.db
Data análise: 04/09/2025 15:08:05

Total de tabelas: 3

--- TABELA: memory_nodes ---
Colunas:
  - node_id (TEXT) 
  - node_type (TEXT) 
  - content (TEXT) 
  - embeddings (TEXT) 
  - metadata (TEXT) 
  - created_at (TIMESTAMP) 
Total registros: 29
Sample (5 primeiros registros):
  1: ('bd27fc13c107a402ad4cdbf77c4ebf93', 'contracts', '{"filename": "ContratoRecupJudicial.pdf", "actors": [], "dates": [], "irregularities": [], "evidence": [], "causal_relations": [], "patterns": [], "v... [TRUNCADO]
  2: ('4cec5263b732cdd47338f5ce6a4f17bd', 'contracts', '{"filename": "ContratoRecupJudicial_2.pdf", "actors": [], "dates": [], "irregularities": [], "evidence": [], "causal_relations": [], "patterns": [], ... [TRUNCADO]
  3: ('ffe78b8c623ef8c0f055d136c46ba468', 'contracts', '{"filename": "ContratoRecupJudicial_3.pdf", "actors": [], "dates": [], "irregularities": [], "evidence": [], "causal_relations": [], "patterns": [], ... [TRUNCADO]
  4: ('c7684866c3f5ee6c3ee52cd74d17cb63', 'contracts', '{"filename": "ContratoRecupJudicial_4.pdf", "actors": [], "dates": [], "irregularities": [], "evidence": [], "causal_relations": [], "patterns": [], ... [TRUNCADO]
  5: ('810ad13c5e8dcedeeef8e3414920a427', 'contracts', '{"filename": "ContratoRecupJudicial_5.pdf", "actors": [], "dates": [], "irregularities": [], "evidence": [], "causal_relations": [], "patterns": [], ... [TRUNCADO]

--- TABELA: memory_edges ---
Colunas:
  - edge_id (TEXT) 
  - source_node (TEXT) 
  - target_node (TEXT) 
  - edge_type (TEXT) 
  - weight (REAL) 
  - metadata (TEXT) 
Total registros: 0

--- TABELA: temporal_events ---
Colunas:
  - event_id (TEXT) 
  - event_date (TEXT) 
  - event_description (TEXT) 
  - actors (TEXT) 
  - evidence_refs (TEXT) 
  - importance (INTEGER) 
  - metadata (TEXT) 
Total registros: 0

================================================================================
FIM DOCUMENTO: deep_memory.db
REFERÊNCIA: doc14-referencia
INTEGRIDADE: VERIFICADA
================================================================================

