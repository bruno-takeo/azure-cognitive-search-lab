# 📥 Ingestão de Conteúdo para IA

Nesta etapa, preparei os dados brutos que seriam utilizados pelo mecanismo de busca cognitiva no Azure. O objetivo foi disponibilizar uma coleção de documentos (simulações de reviews de usuários) para que pudessem ser processados e indexados.

## ✅ Etapas Realizadas

### 1. Criação do Recurso Azure AI Services

- Acesse o [portal do Azure](https://portal.azure.com)
- Busque por “Azure AI Services”
- Criei um novo recurso com os seguintes parâmetros:
  - Nome: `ai-review-service`
  - Região: Brazil South
  - Plano: Gratuito (F0)

### 2. Criação da Storage Account

- Nome da conta: `reviewstorageai`
- Ativei o acesso público aos blobs (⚠️ **somente para fins de teste**):
  - Em "Configurações > Rede", mantive como `All networks`
  - Em "Containers", alterei o nível de acesso para `Public read access for blobs only`

### 3. Criação do Container

- Nome do container: `userreviews`
- Permissões: Acesso público para leitura de blobs

### 4. Upload dos Arquivos

- Carreguei arquivos `.json` simulando avaliações de usuários sobre produtos fictícios
- Os arquivos seguem o padrão:
  ```json
  {
    "id": "1",
    "title": "Produto excelente",
    "content": "A entrega foi rápida e o produto superou minhas expectativas.",
    "author": "João da Silva",
    "rating": 5
  }

### 📝Observações
- A escolha do formato .json facilita a leitura e indexação no Azure Search.
- A permissão pública foi temporária e será revogada após a finalização dos testes.
