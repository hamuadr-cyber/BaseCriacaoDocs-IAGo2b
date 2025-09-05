# Documentos Referência para construção do doc35

**Nome In Natura:** doc35: header.bin

**Data de Processamento:** 04/09/2025 15:08:10

**Processo RJ:** 1039604-94.2023.8.26.0405

**Inquérito MPF:** 1.16.000.001860/2025-10

**Cadeia de Custódia:** MANTIDA (Hashes SHA-256 registrados)

**Audit Log:** MEGA_AUDIT_20250904_150743.log

---

## Temática do Documento

O **doc35** trata do tema: **Cabeçalhos binários e metadados estruturais**

Os documentos abaixo são utilizados como **referência para extração desta temática específica**, não para uso integral. A referência pode conter múltiplos temas e complexidades, podendo apresentar duplicidades que serão tratadas nas fases posteriores.

## Controles de Segurança e Auditoria

- **Backup de Segurança:** Criado antes do processamento
- **Hashes de Integridade:** Calculados para todos os arquivos
- **Log de Auditoria:** Todas as operações registradas
- **Normalização UTF-8:** Aplicada preservando conteúdo original
- **Classificação LGPD:** Documentos classificados por sensibilidade

---

## Arquivos/Documentos Utilizados como Referência

1. `analysis_header.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `534f2264eec2ae03bc4be47877144dbe3462635e330fbf86b8fbba1a1035644d`
   - Sensibilidade: ALTA_SENSIBILIDADE

2. `analysis_header_20250826_204000.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `4763db99ae8cf60c1f05fc7d6d85ee91d29f21541ea342d347f2b4f68e47b302`
   - Sensibilidade: ALTA_SENSIBILIDADE

3. `reconciliado_header.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `136db4a4bf71a40327baddedc4a1b131eae69405b0418081a358bbba52ebac57`
   - Sensibilidade: ALTA_SENSIBILIDADE

4. `chroma.sqlite3`
   - Tipo: SQLite - Banco de dados
   - Hash SHA-256: `b0a17bc7285ba3ebf2a0a914ce7bf392aaf002663362c8bc6508f65fdf1336a6`
   - Sensibilidade: ALTA_SENSIBILIDADE

---

\newpage

================================================================================
DOCUMENTO: analysis_header.json
REFERÊNCIA: doc35-referencia
PROCESSADO EM: 04/09/2025 15:08:11
HASH ORIGINAL: 534f2264eec2ae03bc4be47877144dbe3462635e330fbf86b8fbba1a1035644d
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
  file: header.bin
  path: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/go2b_vectors/dec28d40-8b7c-4803-a377-d760cbebc655/header.bin
  timestamp: 2025-08-30T20:20:09.895312
  size: 100
  type: binary
  descricao: 
  is_critical: False
content_extraction:
  success: True
  preview: [Arquivo binario: header.bin]
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
FIM DOCUMENTO: analysis_header.json
REFERÊNCIA: doc35-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: analysis_header_20250826_204000.json
REFERÊNCIA: doc35-referencia
PROCESSADO EM: 04/09/2025 15:08:11
HASH ORIGINAL: 4763db99ae8cf60c1f05fc7d6d85ee91d29f21541ea342d347f2b4f68e47b302
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 2 chaves
Chaves principais:
  - tipo: str
  - arquivo: str

=== CONTEÚDO JSON ===
tipo: binary
arquivo: header.bin

================================================================================
FIM DOCUMENTO: analysis_header_20250826_204000.json
REFERÊNCIA: doc35-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: reconciliado_header.json
REFERÊNCIA: doc35-referencia
PROCESSADO EM: 04/09/2025 15:08:11
HASH ORIGINAL: 136db4a4bf71a40327baddedc4a1b131eae69405b0418081a358bbba52ebac57
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 4 chaves
Chaves principais:
  - tipo: str
  - arquivo: str
  - metadata: dict
  - reconciliation_insights: dict

=== CONTEÚDO JSON ===
tipo: binary
arquivo: header.bin
metadata:
  reconciliado_v9: True
  timestamp_reconciliacao: 2025-09-01T17:22:46.261122
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
FIM DOCUMENTO: reconciliado_header.json
REFERÊNCIA: doc35-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: chroma.sqlite3
REFERÊNCIA: doc35-referencia
PROCESSADO EM: 04/09/2025 15:08:11
HASH ORIGINAL: b0a17bc7285ba3ebf2a0a914ce7bf392aaf002663362c8bc6508f65fdf1336a6
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE BANCO DE DADOS SQLITE ===
Arquivo: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/Bak-ExclusaoPossivelExtracao70jsons/checagem02/doc35/chroma.sqlite3
Data análise: 04/09/2025 15:08:11

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
REFERÊNCIA: doc35-referencia
INTEGRIDADE: VERIFICADA
================================================================================

