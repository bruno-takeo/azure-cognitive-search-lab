# 🧠 Criação de Índices Inteligentes

Nesta fase, configurei o Azure AI Search para processar os arquivos enviados e criar um índice pesquisável. Isso permitiu a automatização de consultas com base no conteúdo dos documentos.

## 🔧 Etapas Executadas

### 1. Criação do Serviço de Pesquisa Cognitiva

- Nome do serviço: `aisearch-bruno`
- Tipo: Azure Cognitive Search
- Preço: Free (F)

### 2. Conexão com o Azure Blob Storage

- Configurei o conector para o container `userreviews`
- Fonte de dados: Azure Blob
- Formato: JSON
- Autenticação: chave de conta de armazenamento

### 3. Skillset (Conjunto de habilidades)

- Adicionei habilidades automáticas como:
  - Detecção de idioma
  - Extração de palavras-chave
  - Sentiment analysis (análise de sentimento)

### 4. Criação do Índice

- Nome do índice: `reviews-index`
- Campos definidos:
  - `id` (Chave primária)
  - `title` (Texto pesquisável)
  - `content` (Texto pesquisável e analisável)
  - `author` (Facetable e pesquisável)
  - `rating` (Filtrável e ordenável)
  - `sentiment` (extraído pela IA)

### 5. Indexador

- Nome: `indexador-reviews`
- Agendado para atualização a cada 5 minutos (modo teste)

## ✅ Resultados

- Índice criado com sucesso e dados foram extraídos automaticamente com enriquecimento via AI.
- A análise de sentimentos funcionou bem na maioria dos textos.
