# Documentos Referência para construção do doc23

**Nome In Natura:** doc23: go2b_analyses.db

**Data de Processamento:** 04/09/2025 15:08:06

**Processo RJ:** 1039604-94.2023.8.26.0405

**Inquérito MPF:** 1.16.000.001860/2025-10

**Cadeia de Custódia:** MANTIDA (Hashes SHA-256 registrados)

**Audit Log:** MEGA_AUDIT_20250904_150743.log

---

## Temática do Documento

O **doc23** trata do tema: **Análises GO2B estruturadas e processamento documental**

Os documentos abaixo são utilizados como **referência para extração desta temática específica**, não para uso integral. A referência pode conter múltiplos temas e complexidades, podendo apresentar duplicidades que serão tratadas nas fases posteriores.

## Controles de Segurança e Auditoria

- **Backup de Segurança:** Criado antes do processamento
- **Hashes de Integridade:** Calculados para todos os arquivos
- **Log de Auditoria:** Todas as operações registradas
- **Normalização UTF-8:** Aplicada preservando conteúdo original
- **Classificação LGPD:** Documentos classificados por sensibilidade

---

## Arquivos/Documentos Utilizados como Referência

1. `analysis_go2b_analyses_20250826_204000.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `bd2e6a97c1dac0176bb7fe89cef2a4a4b28ae4479115c40a84490e399ea3219e`
   - Sensibilidade: ALTA_SENSIBILIDADE

2. `reconciliado_go2b_analyses.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `0bef546fb0342a87d6cf4e6d8676ea16d286bd32e73e09f3f4ddf28c8b1c97e2`
   - Sensibilidade: ALTA_SENSIBILIDADE

3. `go2b_analyses.db`
   - Tipo: SQLite - Banco de dados
   - Hash SHA-256: `4fce986cd735d067243c163d666a8b27058c8984c61fc09c0bd7566b8e53c9da`
   - Sensibilidade: ALTA_SENSIBILIDADE

---

\newpage

================================================================================
DOCUMENTO: analysis_go2b_analyses_20250826_204000.json
REFERÊNCIA: doc23-referencia
PROCESSADO EM: 04/09/2025 15:08:06
HASH ORIGINAL: bd2e6a97c1dac0176bb7fe89cef2a4a4b28ae4479115c40a84490e399ea3219e
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
arquivo: go2b_analyses.db
tabelas:
  [0]:
    document_analyses
  [1]:
    analysis_sessions
  [2]:
    actors
  [3]:
    timeline_events
  [4]:
    analyses
estrutura:
  document_analyses:
    [0]:
      [0]:
        0
      [1]:
        doc_id
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
        filename
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
        analysis_date
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
        doc_type
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
        legal_area
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
        key_points
      [2]:
        TEXT
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
        risks
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
        opportunities
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [8]:
      [0]:
        8
      [1]:
        legal_thesis
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [9]:
      [0]:
        9
      [1]:
        recommendations
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [10]:
      [0]:
        10
      [1]:
        full_analysis
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [11]:
      [0]:
        11
      [1]:
        raw_content
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [12]:
      [0]:
        12
      [1]:
        irregularities
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [13]:
      [0]:
        13
      [1]:
        evidence_strength
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [14]:
      [0]:
        14
      [1]:
        connected_docs
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [15]:
      [0]:
        15
      [1]:
        timeline_events
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [16]:
      [0]:
        16
      [1]:
        actors_mentioned
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [17]:
      [0]:
        17
      [1]:
        embeddings_ids
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  analysis_sessions:
    [0]:
      [0]:
        0
      [1]:
        session_id
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
        session_date
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
        documents_analyzed
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
        consolidated_insights
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
        legal_strategy
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
        case_progress
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  actors:
    [0]:
      [0]:
        0
      [1]:
        actor_id
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
        0
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        type
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
        role
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
        documents_mentioned
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
        behavior_pattern
      [2]:
        TEXT
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
        risk_level
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  timeline_events:
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
        date
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
        description
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
        doc_references
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
        legal_implications
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
        actors_involved
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  analyses:
    [0]:
      [0]:
        0
      [1]:
        doc_id
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
        filename
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
        analysis_date
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
        doc_type
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
        legal_area
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
        key_points
      [2]:
        TEXT
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
        risks
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
        opportunities
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [8]:
      [0]:
        8
      [1]:
        legal_thesis
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [9]:
      [0]:
        9
      [1]:
        recommendations
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [10]:
      [0]:
        10
      [1]:
        full_analysis
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [11]:
      [0]:
        11
      [1]:
        irregularities
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [12]:
      [0]:
        12
      [1]:
        evidence_strength
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [13]:
      [0]:
        13
      [1]:
        timeline_events
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [14]:
      [0]:
        14
      [1]:
        actors_mentioned
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [15]:
      [0]:
        15
      [1]:
        raw_content
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
descricao: Base an√°lises SQLite

================================================================================
FIM DOCUMENTO: analysis_go2b_analyses_20250826_204000.json
REFERÊNCIA: doc23-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: reconciliado_go2b_analyses.json
REFERÊNCIA: doc23-referencia
PROCESSADO EM: 04/09/2025 15:08:06
HASH ORIGINAL: 0bef546fb0342a87d6cf4e6d8676ea16d286bd32e73e09f3f4ddf28c8b1c97e2
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
arquivo: go2b_analyses.db
tabelas:
  [0]:
    document_analyses
  [1]:
    analysis_sessions
  [2]:
    actors
  [3]:
    timeline_events
  [4]:
    analyses
estrutura:
  document_analyses:
    [0]:
      [0]:
        0
      [1]:
        doc_id
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
        filename
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
        analysis_date
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
        doc_type
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
        legal_area
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
        key_points
      [2]:
        TEXT
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
        risks
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
        opportunities
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [8]:
      [0]:
        8
      [1]:
        legal_thesis
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [9]:
      [0]:
        9
      [1]:
        recommendations
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [10]:
      [0]:
        10
      [1]:
        full_analysis
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [11]:
      [0]:
        11
      [1]:
        raw_content
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [12]:
      [0]:
        12
      [1]:
        irregularities
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [13]:
      [0]:
        13
      [1]:
        evidence_strength
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [14]:
      [0]:
        14
      [1]:
        connected_docs
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [15]:
      [0]:
        15
      [1]:
        timeline_events
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [16]:
      [0]:
        16
      [1]:
        actors_mentioned
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [17]:
      [0]:
        17
      [1]:
        embeddings_ids
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  analysis_sessions:
    [0]:
      [0]:
        0
      [1]:
        session_id
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
        session_date
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
        documents_analyzed
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
        consolidated_insights
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
        legal_strategy
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
        case_progress
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  actors:
    [0]:
      [0]:
        0
      [1]:
        actor_id
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
        0
      [4]:
        None
      [5]:
        0
    [2]:
      [0]:
        2
      [1]:
        type
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
        role
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
        documents_mentioned
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
        behavior_pattern
      [2]:
        TEXT
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
        risk_level
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  timeline_events:
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
        date
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
        description
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
        doc_references
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
        legal_implications
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
        actors_involved
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
  analyses:
    [0]:
      [0]:
        0
      [1]:
        doc_id
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
        filename
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
        analysis_date
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
        doc_type
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
        legal_area
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
        key_points
      [2]:
        TEXT
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
        risks
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
        opportunities
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [8]:
      [0]:
        8
      [1]:
        legal_thesis
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [9]:
      [0]:
        9
      [1]:
        recommendations
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [10]:
      [0]:
        10
      [1]:
        full_analysis
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [11]:
      [0]:
        11
      [1]:
        irregularities
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [12]:
      [0]:
        12
      [1]:
        evidence_strength
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [13]:
      [0]:
        13
      [1]:
        timeline_events
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [14]:
      [0]:
        14
      [1]:
        actors_mentioned
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
    [15]:
      [0]:
        15
      [1]:
        raw_content
      [2]:
        TEXT
      [3]:
        0
      [4]:
        None
      [5]:
        0
descricao: Base an√°lises SQLite
metadata:
  reconciliado_v9: True
  timestamp_reconciliacao: 2025-09-01T17:23:18.442557
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
FIM DOCUMENTO: reconciliado_go2b_analyses.json
REFERÊNCIA: doc23-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: go2b_analyses.db
REFERÊNCIA: doc23-referencia
PROCESSADO EM: 04/09/2025 15:08:06
HASH ORIGINAL: 4fce986cd735d067243c163d666a8b27058c8984c61fc09c0bd7566b8e53c9da
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE BANCO DE DADOS SQLITE ===
Arquivo: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/Bak-ExclusaoPossivelExtracao70jsons/checagem02/doc23/go2b_analyses.db
Data análise: 04/09/2025 15:08:06

Total de tabelas: 5

--- TABELA: document_analyses ---
Colunas:
  - doc_id (TEXT) 
  - filename (TEXT) 
  - analysis_date (TEXT) 
  - doc_type (TEXT) 
  - legal_area (TEXT) 
  - key_points (TEXT) 
  - risks (TEXT) 
  - opportunities (TEXT) 
  - legal_thesis (TEXT) 
  - recommendations (TEXT) 
  - full_analysis (TEXT) 
  - raw_content (TEXT) 
  - irregularities (TEXT) 
  - evidence_strength (TEXT) 
  - connected_docs (TEXT) 
  - timeline_events (TEXT) 
  - actors_mentioned (TEXT) 
  - embeddings_ids (TEXT) 
Total registros: 0

--- TABELA: analysis_sessions ---
Colunas:
  - session_id (TEXT) 
  - session_date (TEXT) 
  - documents_analyzed (TEXT) 
  - consolidated_insights (TEXT) 
  - legal_strategy (TEXT) 
  - case_progress (TEXT) 
Total registros: 0

--- TABELA: actors ---
Colunas:
  - actor_id (TEXT) 
  - name (TEXT) 
  - type (TEXT) 
  - role (TEXT) 
  - documents_mentioned (TEXT) 
  - behavior_pattern (TEXT) 
  - risk_level (TEXT) 
Total registros: 0

--- TABELA: timeline_events ---
Colunas:
  - event_id (TEXT) 
  - date (TEXT) 
  - description (TEXT) 
  - doc_references (TEXT) 
  - legal_implications (TEXT) 
  - actors_involved (TEXT) 
Total registros: 0

--- TABELA: analyses ---
Colunas:
  - doc_id (TEXT) 
  - filename (TEXT) 
  - analysis_date (TEXT) 
  - doc_type (TEXT) 
  - legal_area (TEXT) 
  - key_points (TEXT) 
  - risks (TEXT) 
  - opportunities (TEXT) 
  - legal_thesis (TEXT) 
  - recommendations (TEXT) 
  - full_analysis (TEXT) 
  - irregularities (TEXT) 
  - evidence_strength (TEXT) 
  - timeline_events (TEXT) 
  - actors_mentioned (TEXT) 
  - raw_content (TEXT) 
Total registros: 415
Sample (5 primeiros registros):
  1: ('8271b1e8e5574692', 'Dez2023NegociacaoInicialCtoRJ.pdf', '2025-08-25T23:42:27.176944', 'email thread', 'Recuperação Judicial', '["Negociação inicial de honorários com PL Consultoria", "Valor acordado... [TRUNCADO]
  2: ('706100194492b2c3', 'Legal Document Matrix Analysis - Claude.pdf', '2025-08-25T23:42:40.173155', 'Matriz de Análise Legal Consolidada', 'Recuperação Judicial e Direito Falimentar', '["Rede de impedim... [TRUNCADO]
  3: ('02e377c27b8cdc7c', 'Go2B Project Protocol Initialization - Claude_1.pdf', '2025-08-25T23:44:05.280832', 'documento', 'recuperação judicial', '["Análise de Go2B Project Protocol Initialization - Clau... [TRUNCADO]
  4: ('b6022caa848c3aff', 'ComunicacoeseAlertas-FaltaAtuaçaoPL-Jur_2.pdf', '2025-08-25T23:44:30.946440', 'Comunicações por email sobre processos judiciais', 'Recuperação Judicial e Direito Empresarial', '... [TRUNCADO]
  5: ('2b54fe486cf17105', 'ProcessoqueResultouApropriacaoCredito-Dagoberto_2.pdf', '2025-08-25T23:44:43.840834', 'e-mail thread', 'Recuperação Judicial e Direito Empresarial', '["Acordo com CMZ não cumprid... [TRUNCADO]

================================================================================
FIM DOCUMENTO: go2b_analyses.db
REFERÊNCIA: doc23-referencia
INTEGRIDADE: VERIFICADA
================================================================================

