# Documentos Referência para construção do doc09

**Nome In Natura:** doc09: chroma

**Data de Processamento:** 04/09/2025 15:08:05

**Processo RJ:** 1039604-94.2023.8.26.0405

**Inquérito MPF:** 1.16.000.001860/2025-10

**Cadeia de Custódia:** MANTIDA (Hashes SHA-256 registrados)

**Audit Log:** MEGA_AUDIT_20250904_150743.log

---

## Temática do Documento

O **doc09** trata do tema: **Bases de dados ChromaDB e sistemas de busca vetorial**

Os documentos abaixo são utilizados como **referência para extração desta temática específica**, não para uso integral. A referência pode conter múltiplos temas e complexidades, podendo apresentar duplicidades que serão tratadas nas fases posteriores.

## Controles de Segurança e Auditoria

- **Backup de Segurança:** Criado antes do processamento
- **Hashes de Integridade:** Calculados para todos os arquivos
- **Log de Auditoria:** Todas as operações registradas
- **Normalização UTF-8:** Aplicada preservando conteúdo original
- **Classificação LGPD:** Documentos classificados por sensibilidade

---

## Arquivos/Documentos Utilizados como Referência

1. `reconciliado_chroma.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `ba5fa5d642cf96d01d3dd91f45fd26dd6d1f2d6c6cb291d692b4961e1de94c3c`
   - Sensibilidade: ALTA_SENSIBILIDADE

2. `analysis_chroma.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `147af89332f4385cbe850b9661b9168e4caf49c50c8b7c2d5c11d80623ca64e5`
   - Sensibilidade: ALTA_SENSIBILIDADE

3. `chroma.sqlite3`
   - Tipo: SQLite - Banco de dados
   - Hash SHA-256: `b0a17bc7285ba3ebf2a0a914ce7bf392aaf002663362c8bc6508f65fdf1336a6`
   - Sensibilidade: ALTA_SENSIBILIDADE

---

\newpage

================================================================================
DOCUMENTO: reconciliado_chroma.json
REFERÊNCIA: doc09-referencia
PROCESSADO EM: 04/09/2025 15:08:05
HASH ORIGINAL: ba5fa5d642cf96d01d3dd91f45fd26dd6d1f2d6c6cb291d692b4961e1de94c3c
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
arquivo: chroma.sqlite3
tabelas:
  [0]:
    migrations
  [1]:
    acquire_write
  [2]:
    collection_metadata
  [3]:
    segment_metadata
  [4]:
    tenants
  [5]:
    databases
  [6]:
    collections
  [7]:
    maintenance_log
  [8]:
    segments
  [9]:
    embeddings
  [10]:
    embedding_metadata
  [11]:
    max_seq_id
  [12]:
    embedding_fulltext_search
  [13]:
    embedding_fulltext_search_data
  [14]:
    embedding_fulltext_search_idx
  [15]:
    embedding_fulltext_search_content
  [16]:
    embedding_fulltext_search_docsize
  [17]:
    embedding_fulltext_search_config
  [18]:
    embeddings_queue
  [19]:
    embeddings_queue_config
estrutura:
  migrations:
    [0]:
      [0]:
        0
      [1]:
        dir
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        1
    [1]:
      [0]:
        1
      [1]:
        version
      [2]:
        INTEGER
      [3]:
        1
      [4]:
        None
      [5]:
        2
    [2]:
      [0]:
        2
      [1]:
        filename
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [3]:
      [0]:
        3
      [1]:
        sql
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [4]:
      [0]:
        4
      [1]:
        hash
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
  acquire_write:
    [0]:
      [0]:
        0
      [1]:
        id
      [2]:
        INTEGER
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
        lock_status
      [2]:
        INTEGER
      [3]:
        1
      [4]:
        None
      [5]:
        0
  collection_metadata:
    [0]:
      [0]:
        0
      [1]:
        collection_id
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
        key
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        2
    [2]:
      [0]:
        2
      [1]:
        str_value
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
        int_value
      [2]:
        INTEGER
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
        float_value
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
        bool_value
      [2]:
        INTEGER
      [3]:
        0
      [4]:
        None
      [5]:
        0
  segment_metadata:
    [0]:
      [0]:
        0
      [1]:
        segment_id
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
        key
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        2
    [2]:
      [0]:
        2
      [1]:
        str_value
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
        int_value
      [2]:
        INTEGER
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
        float_value
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
        bool_value
      [2]:
        INTEGER
      [3]:
        0
      [4]:
        None
      [5]:
        0
  tenants:
    [0]:
      [0]:
        0
      [1]:
        id
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        1
  databases:
    [0]:
      [0]:
        0
      [1]:
        id
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
        name
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        tenant_id
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
  collections:
    [0]:
      [0]:
        0
      [1]:
        id
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
        name
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        dimension
      [2]:
        INTEGER
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
        database_id
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [4]:
      [0]:
        4
      [1]:
        config_json_str
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  maintenance_log:
    [0]:
      [0]:
        0
      [1]:
        id
      [2]:
        INT
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
        timestamp
      [2]:
        INT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        operation
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
  segments:
    [0]:
      [0]:
        0
      [1]:
        id
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
        type
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        scope
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [3]:
      [0]:
        3
      [1]:
        collection
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
  embeddings:
    [0]:
      [0]:
        0
      [1]:
        id
      [2]:
        INTEGER
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
        segment_id
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        embedding_id
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [3]:
      [0]:
        3
      [1]:
        seq_id
      [2]:
        BLOB
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [4]:
      [0]:
        4
      [1]:
        created_at
      [2]:
        TIMESTAMP
      [3]:
        1
      [4]:
        CURRENT_TIMESTAMP
      [5]:
        0
  embedding_metadata:
    [0]:
      [0]:
        0
      [1]:
        id
      [2]:
        INTEGER
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
        key
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        2
    [2]:
      [0]:
        2
      [1]:
        string_value
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
        int_value
      [2]:
        INTEGER
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
        float_value
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
        bool_value
      [2]:
        INTEGER
      [3]:
        0
      [4]:
        None
      [5]:
        0
  max_seq_id:
    [0]:
      [0]:
        0
      [1]:
        segment_id
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
        seq_id
      [2]:
        INTEGER
      [3]:
        0
      [4]:
        None
      [5]:
        0
  embedding_fulltext_search:
    [0]:
      [0]:
        0
      [1]:
        string_value
      [2]:
        
      [3]:
        0
      [4]:
        None
      [5]:
        0
  embedding_fulltext_search_data:
    [0]:
      [0]:
        0
      [1]:
        id
      [2]:
        INTEGER
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
        block
      [2]:
        BLOB
      [3]:
        0
      [4]:
        None
      [5]:
        0
  embedding_fulltext_search_idx:
    [0]:
      [0]:
        0
      [1]:
        segid
      [2]:
        
      [3]:
        1
      [4]:
        None
      [5]:
        1
    [1]:
      [0]:
        1
      [1]:
        term
      [2]:
        
      [3]:
        1
      [4]:
        None
      [5]:
        2
    [2]:
      [0]:
        2
      [1]:
        pgno
      [2]:
        
      [3]:
        0
      [4]:
        None
      [5]:
        0
  embedding_fulltext_search_content:
    [0]:
      [0]:
        0
      [1]:
        id
      [2]:
        INTEGER
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
        c0
      [2]:
        
      [3]:
        0
      [4]:
        None
      [5]:
        0
  embedding_fulltext_search_docsize:
    [0]:
      [0]:
        0
      [1]:
        id
      [2]:
        INTEGER
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
        sz
      [2]:
        BLOB
      [3]:
        0
      [4]:
        None
      [5]:
        0
  embedding_fulltext_search_config:
    [0]:
      [0]:
        0
      [1]:
        k
      [2]:
        
      [3]:
        1
      [4]:
        None
      [5]:
        1
    [1]:
      [0]:
        1
      [1]:
        v
      [2]:
        
      [3]:
        0
      [4]:
        None
      [5]:
        0
  embeddings_queue:
    [0]:
      [0]:
        0
      [1]:
        seq_id
      [2]:
        INTEGER
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
        created_at
      [2]:
        TIMESTAMP
      [3]:
        1
      [4]:
        CURRENT_TIMESTAMP
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        operation
      [2]:
        INTEGER
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [3]:
      [0]:
        3
      [1]:
        topic
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [4]:
      [0]:
        4
      [1]:
        id
      [2]:
        TEXT
      [3]:
        1
      [4]:
        None
      [5]:
        0
    [5]:
      [0]:
        5
      [1]:
        vector
      [2]:
        BLOB
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
        encoding
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [7]:
      [0]:
        7
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
  embeddings_queue_config:
    [0]:
      [0]:
        0
      [1]:
        id
      [2]:
        INTEGER
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
        config_json_str
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
descricao: ChromaDB vectors
metadata:
  reconciliado_v9: True
  timestamp_reconciliacao: 2025-09-01T17:23:00.676642
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
FIM DOCUMENTO: reconciliado_chroma.json
REFERÊNCIA: doc09-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: analysis_chroma.json
REFERÊNCIA: doc09-referencia
PROCESSADO EM: 04/09/2025 15:08:05
HASH ORIGINAL: 147af89332f4385cbe850b9661b9168e4caf49c50c8b7c2d5c11d80623ca64e5
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
  file: chroma.sqlite3
  path: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/go2b_vectors/chroma.sqlite3
  timestamp: 2025-09-01T16:38:30.903659
  size: 136769536
  type: database
  descricao: 
  is_critical: False
  preservacao: 100% conteudo mantido
content_extraction:
  success: True
  full_content:
    migrations:
      columns:
        [0]:
          dir
        [1]:
          version
        [2]:
          filename
        [3]:
          sql
        [4]:
          hash
      column_types:
        dir: TEXT
        version: INTEGER
        filename: TEXT
        sql: TEXT
        hash: TEXT
      record_count: 16
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
    acquire_write:
      columns:
        [0]:
          id
        [1]:
          lock_status
      column_types:
        id: INTEGER
        lock_status: INTEGER
      record_count: 6
      sample_data:
        [0]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [1]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [2]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [3]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [4]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
    collection_metadata:
      columns:
        [0]:
          collection_id
        [1]:
          key
        [2]:
          str_value
        [3]:
          int_value
        [4]:
          float_value
        [5]:
          bool_value
      column_types:
        collection_id: TEXT
        key: TEXT
        str_value: TEXT
        int_value: INTEGER
        float_value: REAL
        bool_value: INTEGER
      record_count: 1
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
    segment_metadata:
      columns:
        [0]:
          segment_id
        [1]:
          key
        [2]:
          str_value
        [3]:
          int_value
        [4]:
          float_value
        [5]:
          bool_value
      column_types:
        segment_id: TEXT
        key: TEXT
        str_value: TEXT
        int_value: INTEGER
        float_value: REAL
        bool_value: INTEGER
      record_count: 0
      sample_data: None
    tenants:
      columns:
        [0]:
          id
      column_types:
        id: TEXT
      record_count: 1
      sample_data:
        [0]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
    databases:
      columns:
        [0]:
          id
        [1]:
          name
        [2]:
          tenant_id
      column_types:
        id: TEXT
        name: TEXT
        tenant_id: TEXT
      record_count: 1
      sample_data:
        [0]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
    collections:
      columns:
        [0]:
          id
        [1]:
          name
        [2]:
          dimension
        [3]:
          database_id
        [4]:
          config_json_str
      column_types:
        id: TEXT
        name: TEXT
        dimension: INTEGER
        database_id: TEXT
        config_json_str: TEXT
      record_count: 1
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
    maintenance_log:
      columns:
        [0]:
          id
        [1]:
          timestamp
        [2]:
          operation
      column_types:
        id: INT
        timestamp: INT
        operation: TEXT
      record_count: 0
      sample_data: None
    segments:
      columns:
        [0]:
          id
        [1]:
          type
        [2]:
          scope
        [3]:
          collection
      column_types:
        id: TEXT
        type: TEXT
        scope: TEXT
        collection: TEXT
      record_count: 2
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
        [1]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [2]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [3]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
    embeddings:
      columns:
        [0]:
          id
        [1]:
          segment_id
        [2]:
          embedding_id
        [3]:
          seq_id
        [4]:
          created_at
      column_types:
        id: INTEGER
        segment_id: TEXT
        embedding_id: TEXT
        seq_id: BLOB
        created_at: TIMESTAMP
      record_count: 1245
      sample_data: None
    embedding_metadata:
      columns:
        [0]:
          id
        [1]:
          key
        [2]:
          string_value
        [3]:
          int_value
        [4]:
          float_value
        [5]:
          bool_value
      column_types:
        id: INTEGER
        key: TEXT
        string_value: TEXT
        int_value: INTEGER
        float_value: REAL
        bool_value: INTEGER
      record_count: 4980
      sample_data: None
    max_seq_id:
      columns:
        [0]:
          segment_id
        [1]:
          seq_id
      column_types:
        segment_id: TEXT
        seq_id: INTEGER
      record_count: 2
      sample_data:
        [0]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
        [1]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
    embedding_fulltext_search:
      columns:
        [0]:
          string_value
      column_types:
        string_value: 
      record_count: 1245
      sample_data: None
    embedding_fulltext_search_data:
      columns:
        [0]:
          id
        [1]:
          block
      column_types:
        id: INTEGER
        block: BLOB
      record_count: 12589
      sample_data: None
    embedding_fulltext_search_idx:
      columns:
        [0]:
          segid
        [1]:
          term
        [2]:
          pgno
      column_types:
        segid: 
        term: 
        pgno: 
      record_count: 9496
      sample_data: None
    embedding_fulltext_search_content:
      columns:
        [0]:
          id
        [1]:
          c0
      column_types:
        id: INTEGER
        c0: 
      record_count: 1245
      sample_data: None
    embedding_fulltext_search_docsize:
      columns:
        [0]:
          id
        [1]:
          sz
      column_types:
        id: INTEGER
        sz: BLOB
      record_count: 1245
      sample_data: None
    embedding_fulltext_search_config:
      columns:
        [0]:
          k
        [1]:
          v
      column_types:
        k: 
        v: 
      record_count: 1
      sample_data:
        [0]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
    embeddings_queue:
      columns:
        [0]:
          seq_id
        [1]:
          created_at
        [2]:
          operation
        [3]:
          topic
        [4]:
          id
        [5]:
          vector
        [6]:
          encoding
        [7]:
          metadata
      column_types:
        seq_id: INTEGER
        created_at: TIMESTAMP
        operation: INTEGER
        topic: TEXT
        id: TEXT
        vector: BLOB
        encoding: TEXT
        metadata: TEXT
      record_count: 246
      sample_data: None
    embeddings_queue_config:
      columns:
        [0]:
          id
        [1]:
          config_json_str
      column_types:
        id: INTEGER
        config_json_str: TEXT
      record_count: 1
      sample_data:
        [0]:
          [0]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
          [1]:
            [ESTRUTURA MUITO PROFUNDA - TRUNCADA]
  preview: {'migrations': {'columns': ['dir', 'version', 'filename', 'sql', 'hash'], 'column_types': {'dir': 'TEXT', 'version': 'INTEGER', 'filename': 'TEXT', 'sql': 'TEXT', 'hash': 'TEXT'}, 'record_count': 16, ... [TRUNCADO]
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
FIM DOCUMENTO: analysis_chroma.json
REFERÊNCIA: doc09-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: chroma.sqlite3
REFERÊNCIA: doc09-referencia
PROCESSADO EM: 04/09/2025 15:08:05
HASH ORIGINAL: b0a17bc7285ba3ebf2a0a914ce7bf392aaf002663362c8bc6508f65fdf1336a6
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE BANCO DE DADOS SQLITE ===
Arquivo: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/Bak-ExclusaoPossivelExtracao70jsons/checagem02/doc09/chroma.sqlite3
Data análise: 04/09/2025 15:08:05

Total de tabelas: 20

--- TABELA: migrations ---
Colunas:
  - dir (TEXT) NOT NULL
  - version (INTEGER) NOT NULL
  - filename (TEXT) NOT NULL
  - sql (TEXT) NOT NULL
  - hash (TEXT) NOT NULL
Total registros: 16
Sample (5 primeiros registros):
  1: ('sysdb', 1, '00001-collections.sqlite.sql', 'CREATE TABLE collections (\n    id TEXT PRIMARY KEY,\n    name TEXT NOT NULL,\n    topic TEXT NOT NULL,\n    UNIQUE (name)\n);\n\nCREATE TABLE collection_... [TRUNCADO]
  2: ('sysdb', 2, '00002-segments.sqlite.sql', 'CREATE TABLE segments (\n    id TEXT PRIMARY KEY,\n    type TEXT NOT NULL,\n    scope TEXT NOT NULL,\n    topic TEXT,\n    collection TEXT REFERENCES collect... [TRUNCADO]
  3: ('sysdb', 3, '00003-collection-dimension.sqlite.sql', 'ALTER TABLE collections ADD COLUMN dimension INTEGER;\n', '42d22d0574d31d419c2a0e7f625c93aa')
  4: ('sysdb', 4, '00004-tenants-databases.sqlite.sql', "CREATE TABLE IF NOT EXISTS tenants (\n    id TEXT PRIMARY KEY,\n    UNIQUE (id)\n);\n\nCREATE TABLE IF NOT EXISTS databases (\n    id TEXT PRIMARY K... [TRUNCADO]
  5: ('sysdb', 5, '00005-remove-topic.sqlite.sql', '-- Remove the topic column from the Collections and Segments tables\n\nALTER TABLE collections DROP COLUMN topic;\nALTER TABLE segments DROP COLUMN topic... [TRUNCADO]

--- TABELA: acquire_write ---
Colunas:
  - id (INTEGER) 
  - lock_status (INTEGER) NOT NULL
Total registros: 6
Sample (5 primeiros registros):
  1: (1, 1)
  2: (2, 1)
  3: (3, 1)
  4: (4, 1)
  5: (5, 1)

--- TABELA: collection_metadata ---
Colunas:
  - collection_id (TEXT) 
  - key (TEXT) NOT NULL
  - str_value (TEXT) 
  - int_value (INTEGER) 
  - float_value (REAL) 
  - bool_value (INTEGER) 
Total registros: 1
Sample (5 primeiros registros):
  1: ('d746b69e-7b75-4977-9470-77c60f21321c', 'hnsw:space', 'cosine', None, None, None)

--- TABELA: segment_metadata ---
Colunas:
  - segment_id (TEXT) 
  - key (TEXT) NOT NULL
  - str_value (TEXT) 
  - int_value (INTEGER) 
  - float_value (REAL) 
  - bool_value (INTEGER) 
Total registros: 0

--- TABELA: tenants ---
Colunas:
  - id (TEXT) 
Total registros: 1
Sample (5 primeiros registros):
  1: ('default_tenant',)

--- TABELA: databases ---
Colunas:
  - id (TEXT) 
  - name (TEXT) NOT NULL
  - tenant_id (TEXT) NOT NULL
Total registros: 1
Sample (5 primeiros registros):
  1: ('00000000-0000-0000-0000-000000000000', 'default_database', 'default_tenant')

--- TABELA: collections ---
Colunas:
  - id (TEXT) 
  - name (TEXT) NOT NULL
  - dimension (INTEGER) 
  - database_id (TEXT) NOT NULL
  - config_json_str (TEXT) 
Total registros: 1
Sample (5 primeiros registros):
  1: ('d746b69e-7b75-4977-9470-77c60f21321c', 'go2b_docs', 384, '00000000-0000-0000-0000-000000000000', '{"vector_index":{"hnsw":{"space":"cosine","ef_construction":100,"ef_search":100,"max_neighbors":16,"... [TRUNCADO]

--- TABELA: maintenance_log ---
Colunas:
  - id (INT) 
  - timestamp (INT) NOT NULL
  - operation (TEXT) NOT NULL
Total registros: 0

--- TABELA: segments ---
Colunas:
  - id (TEXT) 
  - type (TEXT) NOT NULL
  - scope (TEXT) NOT NULL
  - collection (TEXT) NOT NULL
Total registros: 2
Sample (5 primeiros registros):
  1: ('dec28d40-8b7c-4803-a377-d760cbebc655', 'urn:chroma:segment/vector/hnsw-local-persisted', 'VECTOR', 'd746b69e-7b75-4977-9470-77c60f21321c')
  2: ('027842f5-eb01-4191-bb29-1e6a533e8b39', 'urn:chroma:segment/metadata/sqlite', 'METADATA', 'd746b69e-7b75-4977-9470-77c60f21321c')

--- TABELA: embeddings ---
Colunas:
  - id (INTEGER) 
  - segment_id (TEXT) NOT NULL
  - embedding_id (TEXT) NOT NULL
  - seq_id (BLOB) NOT NULL
  - created_at (TIMESTAMP) NOT NULL
Total registros: 1245
Sample (5 primeiros registros):
  1: (1, '027842f5-eb01-4191-bb29-1e6a533e8b39', '8271b1e8e5574692_0', 1, '2025-08-26 02:42:27')
  2: (2, '027842f5-eb01-4191-bb29-1e6a533e8b39', '706100194492b2c3_0', 2, '2025-08-26 02:42:40')
  3: (3, '027842f5-eb01-4191-bb29-1e6a533e8b39', '02e377c27b8cdc7c_0', 3, '2025-08-26 02:44:05')
  4: (4, '027842f5-eb01-4191-bb29-1e6a533e8b39', 'b6022caa848c3aff_0', 4, '2025-08-26 02:44:31')
  5: (5, '027842f5-eb01-4191-bb29-1e6a533e8b39', 'b6022caa848c3aff_1', 5, '2025-08-26 02:44:31')

--- TABELA: embedding_metadata ---
Colunas:
  - id (INTEGER) 
  - key (TEXT) NOT NULL
  - string_value (TEXT) 
  - int_value (INTEGER) 
  - float_value (REAL) 
  - bool_value (INTEGER) 
Total registros: 4980
Sample (5 primeiros registros):
  1: (1, 'filename', 'Dez2023NegociacaoInicialCtoRJ.pdf', None, None, None)
  2: (1, 'doc_id', '8271b1e8e5574692', None, None, None)
  3: (1, 'chroma:document', "1Adriano Hamu De: Adriano Hamu <adriano@go2b.com.br> Enviado em: sexta-feira, 15 de dezembro de 2023 12:09 Para: 'Dagoberto Mello lima' Cc: 'Cassiano Almeida'; 'Carin Regina' A... [TRUNCADO]
  4: (1, 'chunk', None, 0, None, None)
  5: (2, 'chroma:document', 'DOCUMENTOS ANALISADOS E INTEGRADOS 1. MATRIZES JSON analise_rj_completa.json: 52 documentos processuais analisados (15.762.027 caracteres) matriz_unificada_go2b_v7.json: Versão... [TRUNCADO]

--- TABELA: max_seq_id ---
Colunas:
  - segment_id (TEXT) 
  - seq_id (INTEGER) 
Total registros: 2
Sample (5 primeiros registros):
  1: ('027842f5-eb01-4191-bb29-1e6a533e8b39', 1245)
  2: ('dec28d40-8b7c-4803-a377-d760cbebc655', 1000)

--- TABELA: embedding_fulltext_search ---
Colunas:
  - string_value () 
Total registros: 1245
Sample (5 primeiros registros):
  1: ("1Adriano Hamu De: Adriano Hamu <adriano@go2b.com.br> Enviado em: sexta-feira, 15 de dezembro de 2023 12:09 Para: 'Dagoberto Mello lima' Cc: 'Cassiano Almeida'; 'Carin Regina' Assunto: RES: Proposta ... [TRUNCADO]
  2: ('DOCUMENTOS ANALISADOS E INTEGRADOS 1. MATRIZES JSON analise_rj_completa.json: 52 documentos processuais analisados (15.762.027 caracteres) matriz_unificada_go2b_v7.json: Versão 7.0 UNIFIED-COMPLETE ... [TRUNCADO]
  3: ('Iniciar conversa com base instruções projeto. ✅ PROTOCOLO GO2B CARREGADO Matriz v7.0: VERIFICADA ✅ Consolidações: 8 arquivos localizados matriz_unificada_go2b_v7.json fusaointegradaGo2bRecupJudicial... [TRUNCADO]
  4: ('1Adriano Hamu De: Fernanda Andreoli <fernanda.andreoli@go2b.com.br> Enviado em: quinta-feira, 1 de agosto de 2024 18:52 Para: \'Carin Regina \' Cc: \'Livia Figueiredo\'; \'Adriano Hamu\' Assunto: Pr... [TRUNCADO]
  5: ("'Carin Regina ' Cc: 'Cleiton Oliveira'; 'Adriano Hamu'; 'Livia Figueiredo ' Assunto: Novo Processo - Execução de Título Extrajudicial - SCF Brazil LI Fundo de Investimento x GO2B, Adriano Hamu e Lid... [TRUNCADO]

--- TABELA: embedding_fulltext_search_data ---
Colunas:
  - id (INTEGER) 
  - block (BLOB) 
Total registros: 12589
Sample (5 primeiros registros):
  1: (1, b'\x89]\x8b\x96\x9e_')
  2: (10, b'\x00\x00\x00\x00\x05\r\x81\x87p\x00\x04\t\x01\x01\x0b\x01\x0f\x0c\x01\x0f\r\x01\x02\x00\x00\x00\x03\x04\x01\x82u\x05\x01\x81w\x06\x01\x81N\x00\x03\x08\x01\x89!\x07\x01\x869\n\x01\x85H\x00\x03\x... [TRUNCADO]
  3: (137438953473, b'\x00\x00\x0f\x9d\x040\x01 e\x810\x04\x82\x0f\x02\x02##\x1d\x04\x85\x17\x01\x04\xa6{\x01\x04\xe91\x02\x04\x9aK\x13\x04\x84h\x15\x04\x85\x17\x01\x04\xa6{\x01\x04\xe91\x02\x04\x9aKU\x04\... [TRUNCADO]
  4: (137438953474, b'\x00\x00\x0f\xc3\xb7s,xy\x84\x11\x81\x17\x81\x08~\x81\x14\x89\x13\x83)\x82,\x82\\\x81Y\x82\x01\x82\x00\x81C\x8d\x1b\x81[\x81m\x81Y\x040 "3\x02\x1c\xb83\x84\x17\x81%\x81\r\x81#\x82<\x8... [TRUNCADO]
  5: (137438953475, b'\x00\x04\x0f\xce\x82\x08\x0c\xa0Q\x8bi\x89P\x01\x0c\xc2\x13\x8eB\x84m\x02\x12\xa7t\x94eC?\x82$!\x01\x08\x99G\xa7"\x01\x81X\xb9[\x830\x81~a\x82\nG\x85\x06\x82*\x82\x07\x83w\x86q\x81\x1... [TRUNCADO]

--- TABELA: embedding_fulltext_search_idx ---
Colunas:
  - segid () NOT NULL
  - term () NOT NULL
  - pgno () 
Total registros: 9496
Sample (5 primeiros registros):
  1: (1, b'', 2)
  2: (1, b'0 "3', 4)
  3: (1, b'0 "b', 6)
  4: (1, b'0 "d', 8)
  5: (1, b'0 "f', 10)

--- TABELA: embedding_fulltext_search_content ---
Colunas:
  - id (INTEGER) 
  - c0 () 
Total registros: 1245
Sample (5 primeiros registros):
  1: (1, "1Adriano Hamu De: Adriano Hamu <adriano@go2b.com.br> Enviado em: sexta-feira, 15 de dezembro de 2023 12:09 Para: 'Dagoberto Mello lima' Cc: 'Cassiano Almeida'; 'Carin Regina' Assunto: RES: Propos... [TRUNCADO]
  2: (2, 'DOCUMENTOS ANALISADOS E INTEGRADOS 1. MATRIZES JSON analise_rj_completa.json: 52 documentos processuais analisados (15.762.027 caracteres) matriz_unificada_go2b_v7.json: Versão 7.0 UNIFIED-COMPLE... [TRUNCADO]
  3: (3, 'Iniciar conversa com base instruções projeto. ✅ PROTOCOLO GO2B CARREGADO Matriz v7.0: VERIFICADA ✅ Consolidações: 8 arquivos localizados matriz_unificada_go2b_v7.json fusaointegradaGo2bRecupJudic... [TRUNCADO]
  4: (4, '1Adriano Hamu De: Fernanda Andreoli <fernanda.andreoli@go2b.com.br> Enviado em: quinta-feira, 1 de agosto de 2024 18:52 Para: \'Carin Regina \' Cc: \'Livia Figueiredo\'; \'Adriano Hamu\' Assunto:... [TRUNCADO]
  5: (5, "'Carin Regina ' Cc: 'Cleiton Oliveira'; 'Adriano Hamu'; 'Livia Figueiredo ' Assunto: Novo Processo - Execução de Título Extrajudicial - SCF Brazil LI Fundo de Investimento x GO2B, Adriano Hamu e ... [TRUNCADO]

--- TABELA: embedding_fulltext_search_docsize ---
Colunas:
  - id (INTEGER) 
  - sz (BLOB) 
Total registros: 1245
Sample (5 primeiros registros):
  1: (1, b'\x9c\x16')
  2: (2, b'\x81\xbah')
  3: (3, b'\xc6\x11')
  4: (4, b'\x81\xa6*')
  5: (5, b'\x81\x93E')

--- TABELA: embedding_fulltext_search_config ---
Colunas:
  - k () NOT NULL
  - v () 
Total registros: 1
Sample (5 primeiros registros):
  1: ('version', 4)

--- TABELA: embeddings_queue ---
Colunas:
  - seq_id (INTEGER) 
  - created_at (TIMESTAMP) NOT NULL
  - operation (INTEGER) NOT NULL
  - topic (TEXT) NOT NULL
  - id (TEXT) NOT NULL
  - vector (BLOB) 
  - encoding (TEXT) 
  - metadata (TEXT) 
Total registros: 246
Sample (5 primeiros registros):
  1: (1000, '2025-08-26 06:49:05', 0, 'persistent://default/default/d746b69e-7b75-4977-9470-77c60f21321c', '9efc91d2d714c006_5', b'\xc6\xaa\x9c<rF\x82<\xdd\xaf\xa0\xbcn%\xa7\xbc\x8a(\x08\xbd\xccd\xcd=B\x92... [TRUNCADO]
  2: (1001, '2025-08-26 06:49:05', 0, 'persistent://default/default/d746b69e-7b75-4977-9470-77c60f21321c', '9efc91d2d714c006_6', b'\xafy\x87<BC\x9b\xbc\xc7f\xa2<`\x06\x82\xbd\x016U\xbd\x86\xf5x\xbdXCT=\t\x... [TRUNCADO]
  3: (1002, '2025-08-26 06:49:06', 0, 'persistent://default/default/d746b69e-7b75-4977-9470-77c60f21321c', '9efc91d2d714c006_7', b'@\'\xd2\xbcP\xc2\xc9=\xb7T\x85\xbd\x07\xb6\x85\xbd,\xca\x90\xbd\xea\xa7\x1... [TRUNCADO]
  4: (1003, '2025-08-26 06:49:06', 0, 'persistent://default/default/d746b69e-7b75-4977-9470-77c60f21321c', '9efc91d2d714c006_8', b'\x1a$\xba<\xbe\x11\xe9=\x88<\xbb\xbc\x12K\xaf<<-\xbd;PF\xeb\xbcd\x99\x8d\x... [TRUNCADO]
  5: (1004, '2025-08-26 06:49:06', 0, 'persistent://default/default/d746b69e-7b75-4977-9470-77c60f21321c', '9efc91d2d714c006_9', b'\x10\x1d\x00\xbd\xbf\xe0\x01=\xd38\xa6\xbd\xc2t\xc5\xbd\x8f\xf0\x9a\xbdw\x... [TRUNCADO]

--- TABELA: embeddings_queue_config ---
Colunas:
  - id (INTEGER) 
  - config_json_str (TEXT) 
Total registros: 1
Sample (5 primeiros registros):
  1: (1, '{"automatically_purge":true,"_type":"EmbeddingsQueueConfigurationInternal"}')

================================================================================
FIM DOCUMENTO: chroma.sqlite3
REFERÊNCIA: doc09-referencia
INTEGRIDADE: VERIFICADA
================================================================================

