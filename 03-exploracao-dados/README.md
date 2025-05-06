# 🔍 Exploração Prática dos Dados

Com o índice pronto, comecei a explorar os dados utilizando a interface de consulta do Azure AI Search. O objetivo era testar o poder de busca cognitiva sobre os dados enriquecidos.

## 🧪 Testes Realizados

### 1. Buscas por Palavra-chave

- Exemplo: `produto excelente`
- Resultado: 2 documentos com título ou conteúdo com essas palavras

### 2. Filtros por Autor

- Exemplo: `author eq 'João da Silva'`
- Retornou todos os reviews desse autor

### 3. Ordenação por Avaliação

- Exemplo: ordenar por `rating desc`
- Retornou do melhor ao pior review

### 4. Busca por Sentimento

- Filtro: `sentiment eq 'positive'`
- Utilizado para encontrar apenas avaliações com sentimento positivo

### 💡 Insights Obtidos
- A análise de sentimentos ajudou a separar feedbacks úteis automaticamente.
- Os filtros por autor e avaliação permitem construir dashboards prontos para insights de marketing.
- Mesmo com dados simulados, o uso do Azure AI Search mostra grande potencial para análise de grandes volumes de texto.

### 🧩 Próximos Passos
- Criar uma interface web simples conectada à API.
- Adicionar mais documentos reais para testes com maior volume.
