# Documentos Referência para construção do doc33

**Nome In Natura:** doc33: go2b_vectorizer_config.json

**Data de Processamento:** 04/09/2025 15:08:10

**Processo RJ:** 1039604-94.2023.8.26.0405

**Inquérito MPF:** 1.16.000.001860/2025-10

**Cadeia de Custódia:** MANTIDA (Hashes SHA-256 registrados)

**Audit Log:** MEGA_AUDIT_20250904_150743.log

---

## Temática do Documento

O **doc33** trata do tema: **Configuração vectorizer e parametrização NLP**

Os documentos abaixo são utilizados como **referência para extração desta temática específica**, não para uso integral. A referência pode conter múltiplos temas e complexidades, podendo apresentar duplicidades que serão tratadas nas fases posteriores.

## Controles de Segurança e Auditoria

- **Backup de Segurança:** Criado antes do processamento
- **Hashes de Integridade:** Calculados para todos os arquivos
- **Log de Auditoria:** Todas as operações registradas
- **Normalização UTF-8:** Aplicada preservando conteúdo original
- **Classificação LGPD:** Documentos classificados por sensibilidade

---

## Arquivos/Documentos Utilizados como Referência

1. `go2b_vectorizer_config.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `f3860f1358aa27fe2d3b4bebe30fb9782763ae4fc1be3196a758b4ec6e999b98`
   - Sensibilidade: ALTA_SENSIBILIDADE

2. `analysis_go2b_vectorizer_config_20250826_204000.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `0d9c0f582033b2cdabea83195cfc747520d9d0644473846320ee92f2a7cc4b84`
   - Sensibilidade: ALTA_SENSIBILIDADE

3. `analysis_go2b_vectorizer_config.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `b7a2cb57d319b9b65816925dbb94b391d28ccd2b8ede0624bc7ac2d11ee0d9b5`
   - Sensibilidade: ALTA_SENSIBILIDADE

4. `reconciliado_go2b_vectorizer_config.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `f268ee55e62521420591d4ce98b20bb0c9433c6aec41da37b1267b57209f0fd9`
   - Sensibilidade: ALTA_SENSIBILIDADE

---

\newpage

================================================================================
DOCUMENTO: go2b_vectorizer_config.json
REFERÊNCIA: doc33-referencia
PROCESSADO EM: 04/09/2025 15:08:10
HASH ORIGINAL: f3860f1358aa27fe2d3b4bebe30fb9782763ae4fc1be3196a758b4ec6e999b98
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 5 chaves
Chaves principais:
  - index_path: str
  - meta_path: str
  - model: str
  - dimensions: int
  - normalized: bool

=== CONTEÚDO JSON ===
index_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/GptAPI/go2b_faiss.index
meta_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/GptAPI/go2b_embeddings_meta.json
model: text-embedding-3-large
dimensions: 3072
normalized: True

================================================================================
FIM DOCUMENTO: go2b_vectorizer_config.json
REFERÊNCIA: doc33-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: analysis_go2b_vectorizer_config_20250826_204000.json
REFERÊNCIA: doc33-referencia
PROCESSADO EM: 04/09/2025 15:08:10
HASH ORIGINAL: 0d9c0f582033b2cdabea83195cfc747520d9d0644473846320ee92f2a7cc4b84
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
arquivo: go2b_vectorizer_config.json
descricao: Config vectorizer
estrutura:
  index_path: str
  meta_path: str
  model: str
  dimensions: int
  normalized: bool
estatisticas:
  tamanho: 327
  chaves_principais:
    [0]:
      index_path
    [1]:
      meta_path
    [2]:
      model
    [3]:
      dimensions
    [4]:
      normalized
  profundidade: 1

================================================================================
FIM DOCUMENTO: analysis_go2b_vectorizer_config_20250826_204000.json
REFERÊNCIA: doc33-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: analysis_go2b_vectorizer_config.json
REFERÊNCIA: doc33-referencia
PROCESSADO EM: 04/09/2025 15:08:10
HASH ORIGINAL: b7a2cb57d319b9b65816925dbb94b391d28ccd2b8ede0624bc7ac2d11ee0d9b5
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
  file: go2b_vectorizer_config.json
  path: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/desenvolvimentos_outros/go2b_vectorizer_config.json
  timestamp: 2025-09-01T16:36:22.414004
  size: 323
  type: json
  descricao: 
  is_critical: False
  preservacao: 100% conteudo mantido
content_extraction:
  success: True
  full_content:
    index_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/GptAPI/go2b_faiss.index
    meta_path: /Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/GptAPI/go2b_embeddings_meta.json
    model: text-embedding-3-large
    dimensions: 3072
    normalized: True
  preview: {'index_path': '/Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/GptAPI/go2b_faiss.index', 'meta_path': '/Users/AdrianoHamu/Desktop/RecupJudicial05062025/BaseAvaliação-Ago2025/Gp... [TRUNCADO]
  error: None
analise_claude:
  analise_ia_completa:
    resumo_documento: Arquivo de configuração técnica para vetorização de documentos da GO2B, contendo parâmetros de indexação e modelo de embeddings
    contexto_caso: Este arquivo faz parte da infraestrutura de análise documental do caso, possivelmente usado para processamento automatizado de documentos relacionados à recuperação judicial
    informacoes_chave:
      [0]:
        Arquivo de configuração para processamento de documentos
      [1]:
        Utilização do modelo text-embedding-3-large
      [2]:
        Localizado em pasta de Recuperação Judicial de junho 2025
      [3]:
        Dimensionalidade de 3072 para vetorização
      [4]:
        Normalização ativada para processamento
    relevancia_juridica: média - documento técnico que evidencia tentativa de organização e análise sistemática de documentos do caso, potencialmente relevante para demonstrar diligência processual
    recomendacoes:
      [0]:
        Preservar arquivo como evidência de metodologia de análise
      [1]:
        Verificar outros arquivos na mesma pasta de Recuperação Judicial
      [2]:
        Avaliar se houve análise automatizada de documentos relevantes
      [3]:
        Documentar cadeia de custódia digital
  irregularidades:
    apropriacao_cmz:
      detectada: False
      evidencias:

      valores:

      responsaveis:

    renuncia_irregular:
      detectada: False
      evidencias:

      timeline:

    impedimento_judicial:
      detectada: False
      evidencias:

      cadeia_interesse:

    negligencia_profissional:
      detectada: False
      padroes:

      exemplos:

    custas_cartas:
      detectada: False
      proposta_go2b: 
      recusa: 
  evidencias_documentais:
    [0]:
      Arquivo de configuração go2b_vectorizer_config.json
    [1]:
      Localização em pasta de Recuperação Judicial de junho 2025
  valores_financeiros:

  datas_relevantes:
    [0]:
      05/06/2025 (data inferida do caminho do arquivo)
  pessoas_mencionadas:
    [0]:
      AdrianoHamu (do caminho do arquivo)
  violacoes_legais:

  nexo_causal:
    elementos:
      [0]:
        Arquivo de configuração técnica
      [1]:
        Contexto de Recuperação Judicial
      [2]:
        Sistema de análise documental
    conexoes:
      [0]:
        Arquivo técnico parte de sistema maior de análise documental do caso
      [1]:
        Localização em pasta específica de Recuperação Judicial indica relação direta com o processo
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
FIM DOCUMENTO: analysis_go2b_vectorizer_config.json
REFERÊNCIA: doc33-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: reconciliado_go2b_vectorizer_config.json
REFERÊNCIA: doc33-referencia
PROCESSADO EM: 04/09/2025 15:08:10
HASH ORIGINAL: f268ee55e62521420591d4ce98b20bb0c9433c6aec41da37b1267b57209f0fd9
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
arquivo: go2b_vectorizer_config.json
descricao: Config vectorizer
estrutura:
  index_path: str
  meta_path: str
  model: str
  dimensions: int
  normalized: bool
estatisticas:
  tamanho: 327
  chaves_principais:
    [0]:
      index_path
    [1]:
      meta_path
    [2]:
      model
    [3]:
      dimensions
    [4]:
      normalized
  profundidade: 1
metadata:
  reconciliado: True
  timestamp_reconciliacao: 2025-09-01T16:52:34.827626
  verdades_aplicadas:
    chunks: 758
    confidence: 0.85
    valores:
      apropriacao_cmz: 600000.0
      divida_ect: 387055636.47
      custas_cartas: 18000.0
      impedimento_interesse: 17000000.0
      prejuizo_total: 782655636.47
  preservacao: 100% conteudo original mantido
  correcoes_aplicadas: 0
reconciliation_insights:
  paradoxos_encontrados:
    [0]:
      Nenhum paradoxo encontrado - o arquivo está consistente com as verdades estabelecidas
  correcoes_aplicadas:
    [0]:
      Nenhuma correção necessária - valores e parâmetros já estão alinhados com as verdades estabelecidas
  informacoes_uteis:
    [0]:
      Arquivo de configuração do vectorizer para o caso GO2B
    [1]:
      Reconciliação realizada em 01/09/2025
    [2]:
      Preservação integral do conteúdo original
    [3]:
      Número total de chunks: 758
    [4]:
      Confidence threshold: 0.85
  evidencias_preservadas:
    [0]:
      Timestamp da reconciliação: 2025-09-01T16:52:34.827626
    [1]:
      Estrutura do arquivo de configuração com 5 campos principais
    [2]:
      Metadata completa com valores financeiros reconciliados
  valores_identificados:
    apropriacao_cmz: 600000.0
    divida_ect: 387055636.47
    custas_cartas: 18000.0
    impedimento_interesse: 17000000.0
    prejuizo_total: 782655636.47
  atores_mapeados:
    GO2B: vítima
    CMZ: parte que efetuou pagamento
    ECT: parte relacionada à dívida
  timeline_eventos:
    [0]:
      data: 2025-09-01
      evento: Reconciliação do arquivo de configuração
  nexo_causal:
    [0]:
      Arquivo de configuração técnica para processamento de dados do caso
    [1]:
      Parte de um sistema maior de análise documental
    [2]:
      Contém parâmetros validados e valores financeiros reconciliados

================================================================================
FIM DOCUMENTO: reconciliado_go2b_vectorizer_config.json
REFERÊNCIA: doc33-referencia
INTEGRIDADE: VERIFICADA
================================================================================

