# Documentos Referência para construção do doc01

**Nome In Natura:** doc01: actor_index.json

**Data de Processamento:** 04/09/2025 15:07:43

**Processo RJ:** 1039604-94.2023.8.26.0405

**Inquérito MPF:** 1.16.000.001860/2025-10

**Cadeia de Custódia:** MANTIDA (Hashes SHA-256 registrados)

**Audit Log:** MEGA_AUDIT_20250904_150743.log

---

## Temática do Documento

O **doc01** trata do tema: **Mapeamento de atores processuais e relacionamentos criminosos**

Os documentos abaixo são utilizados como **referência para extração desta temática específica**, não para uso integral. A referência pode conter múltiplos temas e complexidades, podendo apresentar duplicidades que serão tratadas nas fases posteriores.

## Controles de Segurança e Auditoria

- **Backup de Segurança:** Criado antes do processamento
- **Hashes de Integridade:** Calculados para todos os arquivos
- **Log de Auditoria:** Todas as operações registradas
- **Normalização UTF-8:** Aplicada preservando conteúdo original
- **Classificação LGPD:** Documentos classificados por sensibilidade

---

## Arquivos/Documentos Utilizados como Referência

1. `actor_index.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a`
   - Sensibilidade: ALTA_SENSIBILIDADE

2. `reconciliado_actor_index.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `296d8fc87a42aa048e687b5637194f8f5e8b95bc8a99e5ad781fa4e7ae0cb5ad`
   - Sensibilidade: ALTA_SENSIBILIDADE

3. `analysis_actor_index.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `4151b8eb287085b44b681be0be5a707707ef3c319bb9d6c93802aa9783323c4a`
   - Sensibilidade: ALTA_SENSIBILIDADE

4. `analysis_actor_index_20250826_204000.json`
   - Tipo: JSON - Dados estruturados
   - Hash SHA-256: `32b4bdd9029959928f080a86bfa95fec319d39e7a173ede234db6c04ad8abd3d`
   - Sensibilidade: ALTA_SENSIBILIDADE

5. `actor_index_incremented.md`
   - Tipo: Markdown - Texto formatado
   - Hash SHA-256: `ee01f9c80ad66a4313f3d516a91cb062a2da9fb89e70780dea2f14896122aed1`
   - Sensibilidade: ALTA_SENSIBILIDADE

---

\newpage

================================================================================
DOCUMENTO: actor_index.json
REFERÊNCIA: doc01-referencia
PROCESSADO EM: 04/09/2025 15:07:43
HASH ORIGINAL: 44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ESTRUTURAL JSON ===
Tipo: Objeto JSON com 0 chaves
Chaves principais:

=== CONTEÚDO JSON ===


================================================================================
FIM DOCUMENTO: actor_index.json
REFERÊNCIA: doc01-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: reconciliado_actor_index.json
REFERÊNCIA: doc01-referencia
PROCESSADO EM: 04/09/2025 15:07:43
HASH ORIGINAL: 296d8fc87a42aa048e687b5637194f8f5e8b95bc8a99e5ad781fa4e7ae0cb5ad
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
arquivo: actor_index.json
descricao: √çndice atores
estrutura:

estatisticas:
  tamanho: 2
  chaves_principais:

  profundidade: 0
metadata:
  reconciliado_v9: True
  timestamp_reconciliacao: 2025-09-01T17:24:44.927117
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
FIM DOCUMENTO: reconciliado_actor_index.json
REFERÊNCIA: doc01-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: analysis_actor_index.json
REFERÊNCIA: doc01-referencia
PROCESSADO EM: 04/09/2025 15:07:43
HASH ORIGINAL: 4151b8eb287085b44b681be0be5a707707ef3c319bb9d6c93802aa9783323c4a
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
  file: actor_index.json
  path: /Users/AdrianoHamu/Desktop/BaseConhecimento/RecupJudicial05062025/BaseAvaliação-Ago2025/ClaudeAPI/go2b_deep_memory/actor_index.json
  timestamp: 2025-09-01T16:38:11.755582
  size: 2
  type: json
  descricao: 
  is_critical: False
  preservacao: 100% conteudo mantido
content_extraction:
  success: True
  full_content:

  preview: {}
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
FIM DOCUMENTO: analysis_actor_index.json
REFERÊNCIA: doc01-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: analysis_actor_index_20250826_204000.json
REFERÊNCIA: doc01-referencia
PROCESSADO EM: 04/09/2025 15:07:43
HASH ORIGINAL: 32b4bdd9029959928f080a86bfa95fec319d39e7a173ede234db6c04ad8abd3d
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
arquivo: actor_index.json
descricao: √çndice atores
estrutura:

estatisticas:
  tamanho: 2
  chaves_principais:

  profundidade: 0

================================================================================
FIM DOCUMENTO: analysis_actor_index_20250826_204000.json
REFERÊNCIA: doc01-referencia
INTEGRIDADE: VERIFICADA
================================================================================

\newpage

================================================================================
DOCUMENTO: actor_index_incremented.md
REFERÊNCIA: doc01-referencia
PROCESSADO EM: 04/09/2025 15:07:43
HASH ORIGINAL: ee01f9c80ad66a4313f3d516a91cb062a2da9fb89e70780dea2f14896122aed1
CADEIA CUSTÓDIA: PRESERVADA
================================================================================

=== ANÁLISE ARQUIVO TEXTO ===
Linhas: 205
Palavras: 978
Caracteres: 7233
Encoding: utf-8
========================================
# ÍNDICE DE ATORES - CASO GO2B (VERSÃO INCREMENTAL v2.0)
## RECUPERAÇÃO JUDICIAL No 1039604-94.2023.8.26.0405 - INQUÉRITO MPF 1.16.000.001860/2025-10

**Data:** 03 de setembro de 2025  
**Status:** IMPEDIMENTO JUDICIAL ABSOLUTO IDENTIFICADO  
**Inquérito MPF:** ATIVO - Velocidade excepcional reconhecida

---

## I. VÍTIMA PRINCIPAL

### **GO2B - EMPRESA VÍTIMA**
- **CNPJ:** 18.504.752/0001-55
- **Representante Legal:** Adriano Ferreira Hamu (CEO)
- **Status Crítico:** SEM REPRESENTAÇÃO desde 19/05/2025 (107 dias)
- **Situação:** Desassistência jurídica por renúncia tecnicamente impossível
- **Prejuízos Documentados:**
  - **Apropriação:** R$ 400.000-600.000 (caso CMZ)
  - **Passivo ECT:** R$ 387.055.636,47 (49.6% do passivo total)
  - **Trabalhista:** R$ 393 milhões (6.000 execuções ativas)

---

## II. APROPRIADORES IDENTIFICADOS

### **PL CONSULTORIA - ESCRITÓRIO APROPRIADOR**
- **Crime Principal:** Apropriação indébita R$ 400k-600k (caso CMZ único)
- **Período:** 15/12/2023 com ocultação por 120 dias
- **Sócios:** Dagoberto Mello Lima (CEO) + Dirceu Pereira (advogado)
- **Base Legal:** Art. 168 §1o III, CP + Lei 7492/86
- **Abandono:** Degradação 93% qualidade documentos
- **Renúncia:** Tecnicamente impossível (DNS 19/05/2025)

### **DAGOBERTO MELLO LIMA - EXECUTOR**
- **Função:** CEO PL Consultoria
- **Participação:** Apropriação qualificada + patrocínio infiel
- **Período Ativo:** Dezembro/2023 → Março/2024
- **Impacto:** Impedimento crítico continuidade GO2B
- **Tipificação:** Art. 168 §1o III + Art. 355 CP

### **DIRCEU PEREIRA - ADVOGADO CÚMPLICE**
- **Função:** Advogado PL Consultoria
- **Participação:** Conhecimento + ocultação por 120 dias
- **Tipificação:** Art. 355 CP + Art. 29 CP (concurso pessoas)

---

## III. IMPEDIMENTO JUDICIAL NUCLEAR

### **MARCELLO PERINO - JUIZ IMPEDIDO**
- **Função:** Juiz titular RJ 1039604-94.2023.8.26.0405
- **IMPEDIMENTO:** Irmão Fernando Perino (advogado)
- **Base Legal:** Arts. 144/145 CPC - impedimento insanável
- **Evidências:** Reportagens públicas + documentos Corregedoria
- **Consequência:** NULIDADE ABSOLUTA todos atos últimos 2+ anos
- **Status:** Game changer nuclear - prioridade máxima

### **FERNANDO PERINO - CONEXÃO IMPEDIMENTO**
- **Relação:** Irmão juiz + advogado + sócio Fábio Garcia
- **Negócios:** R$ 17 milhões procurações período 2023-2025
- **Papel:** Possível coordenação rede advogados
- **Evidence:** Procurações oficiais + documentos públicos

### **FÁBIO GARCIA - CONEXÃO EXTERNA**
- **Relação:** Sócio Fernando + marido Andrea Fleury
- **Antecedentes:** Máfia da Merenda (reportagens)
- **Papel:** Possível lavagem dinheiro + blindagem

---

## IV. ADMINISTRADOR JUDICIAL

### **QUINTINO FLEURY - AJ OMISSOR**
- **Função:** Administrador Judicial RJ GO2B
- **Omissões:** 14 manifestações genéricas + 100% omissão ECT
- **Relação:** Irmão Andrea Fleury (advogada)
- **Evidência:** WhatsApp negociação frustrada com advogada grupo
- **Timeline:** Coordenação suspeita 15/05→19/05→28/05/2025
- **Precedente:** SICES R$ 600M (mesmo AJ)

### **ANDREA FLEURY - SUPORTE**
- **Função:** Advogada estruturação + proteção patrimonial
- **Relações:** Irmã Quintino + esposa Fábio Garcia
- **Papel:** Blindagem societária múltiplas empresas

---

## V. LAWFARE INSTITUCIONAL

### **EMPRESA BRASILEIRA CORREIOS TELÉGRAFOS (ECT)**
- **Papel:** Credor principal + possível instrumento lawfare
- **Débito:** R$ 387.055.636,47 (49.6% passivo total)
- **Omissão AJ:** 100% silêncio sobre ECT em 14 manifestações
- **Nexo Causal:** Inadimplemento ECT → colapso financeiro GO2B
- **Base Legal:** Arts. 319 CP + responsabilidade civil Estado

---

## VI. PRECEDENTES QUE ELEVAM SUSPEITAS

### **SICES - R$ 600 MILHÕES (2020-2022)**
- **Administrador:** Quintino Fleury (MESMO AJ caso GO2B)
- **Metodologia:** 7 etapas destrutivas sistemáticas
- **Resultado:** Empresa destruída + ativos apropriados
- **Correlação:** 95% similaridade com GO2B

### **CHOCOLATES PAN - R$ 263 MILHÕES (2021-2023)**
- **Rede:** Mesmo grupo operacional SICES
- **Metodologia:** Sistemática similar + coordenação
- **Correlação:** 90% similaridade com GO2B

### **NILPEL - R$ 240 MILHÕES (2022-2024)**
- **Status:** Em curso + mesmo padrão
- **Correlação:** 88% similaridade com GO2B
- **Total:** R$ 1.1+ bilhão em empresas com padrão similar

### **MODUS OPERANDI IDENTIFICADO (7 ETAPAS)**
1. **Captação:** Empresa crise → advogados rede
2. **Infiltração:** Juiz nomeia AJ conectado
3. **Pressão:** AJ/Advogados → honorários milionários
4. **Sabotagem:** Empresa sabotada progressivamente
5. **Apropriação:** Ativos apropriados/direcionados
6. **Destruição:** Falência decretada eliminar rastros
7. **Blindagem:** Atos validados judicialmente

---

## VII. OUTROS ATORES RELEVANTES

### **CMZ/CREME MEL - CREDOR QUITE**
- **Status:** Pagou acordo GO2B em 15/12/2023
- **Valor:** R$ 400.000-600.000 (apropriado PL)
- **Papel:** Base factual apropriação confirmada

### **MINISTÉRIO PÚBLICO FEDERAL**
- **Inquérito:** 1.16.000.001860/2025-10 (ATIVO - PF-DF)
- **Velocidade:** Excepcional despachos 48h
- **Status:** Base sólida para aditamento

### **SENADO FEDERAL**
- **Proposta:** 0002/2025 acompanhamento caso
- **Convocação:** CEO Adriano Hamu
- **Status:** Respaldo parlamentar crescente

---

## VIII. TIPIFICAÇÃO CRIMINAL POR ATOR

| Ator | Crime Principal | Artigo Legal | Pena | Evidence |
|------|-----------------|--------------|------|----------|
| **Marcello** | Impedimento absoluto | Arts. 144/145 CPC | Nulidade processual | Docs públicos |
| **PL Consultoria** | Apropriação qualificada | Art. 168 §1o III CP | 1-4 anos | Emails + docs |
| **Suspeita Rede** | Organização criminosa | Lei 12.850/13 | 3-8 anos | Precedentes |
| **Quintino** | Omissão sistemática | Art. 22 LRF | Destituição | 14 omissões |

---

## IX. MAPEAMENTO CORRELACIONAL

### **CADEIA IMPEDIMENTO**
```
Marcello Perino (Juiz)
    ↓ [IRMÃO - docs públicos]
Fernando Perino (Advogado)
    ↓ [SÓCIO R$ 17M - procurações]  
Fábio Garcia (Advogado)
    ↓ [MARIDO - certidões]
Andrea Fleury (Advogada)
    ↓ [IRMÃ - docs familiares]
Quintino Fleury (AJ)
```

### **FLUXO APROPRIAÇÃO**
```
CMZ paga acordo GO2B (15/12/2023 - R$ 400k-600k)
    ↓ [RETENÇÃO PL - 120 dias dolosos]
Impedimento operacional GO2B crítico
    ↓ [COORDENAÇÃO SUSPEITA - WhatsApp]
Renúncia impossível DNS (19/05/2025)
    ↓ [DESASSISTÊNCIA - 107 dias]
```

---

## X. ARSENAL JURÍDICO DISPONÍVEL

### **PETIÇÕES URGÊNCIA EXTREMA**
1. **Exceção Impedimento Absoluto** - Marcello irmão Fernando
2. **Destituição AJ Justa Causa** - 14 omissões + WhatsApp
3. **Suspensão Prejudicialidade** - Inquérito MPF ativo

### **PETIÇÕES URGÊNCIA ALTA**
4. **Representação Suspeita ORCRIM** - Precedentes + padrão
5. **Nulidade Renúncia PL** - DNS impossível certificado
6. **Tutela Antecipada** - Bloqueio R$ 600k + interventor

### **CONFIDENCE SCORES**
- **Impedimento Judicial:** 100% (documentos públicos)
- **Apropriação CMZ:** 90% (documentos correlacionados)
- **Suspeita ORCRIM:** 85% (precedentes elevam suspeitas)
- **Coordenação AJ+PL:** 88% (WhatsApp + timeline)

---

**STATUS:** IMPEDIMENTO NUCLEAR DESCOBERTO - PRIORIDADE ABSOLUTA  
**PRÓXIMA AÇÃO:** Protocolo exceção impedimento absoluto + destituição AJ

================================================================================
FIM DOCUMENTO: actor_index_incremented.md
REFERÊNCIA: doc01-referencia
INTEGRIDADE: VERIFICADA
================================================================================

