# Desafio DIO - Azure AI Search com Mineração de Conhecimento

Este repositório contém a entrega do desafio prático da DIO relacionado à aplicação de técnicas de inteligência artificial para mineração de conhecimento, utilizando o Azure AI Search.

## 📚 Aulas do Desafio

- Mineração de Conhecimento  
- Solução de Pesquisa Cognitiva do Azure  
- Enriquecimento de IA  
- Buscas Cognitivas  

## 🔗 Link do Lab

O laboratório foi realizado utilizando o seguinte link oficial da Microsoft:  
👉 [https://aka.ms/ai900-ai-search](https://aka.ms/ai900-ai-search)

## 🧪 Descrição da Aula Prática

Durante a prática, foram realizados os seguintes passos:

1. **Criação de um recurso Azure AI Service**  
   Esse recurso foi o ponto de partida para aplicar as capacidades de IA na análise de documentos.

2. **Configuração de uma conta de armazenamento (Storage Account)**  
   - Permiti acesso anônimo ao Blob (não recomendado em ambientes de produção; foi feito apenas para fins de teste).  
   - Criação de um container para upload de arquivos simulando *reviews* de usuários.

3. **Criação de um mecanismo de busca inteligente (Azure AI Search)**  
   - Utilização do Azure AI Service para automatizar a ingestão, indexação e consulta de documentos.  
   - Foi possível simular buscas cognitivas utilizando os dados carregados.

## 🧠 Objetivo do Desafio

O principal objetivo foi aplicar técnicas de organização e pesquisa de documentos com base em:

- Ingestão de conteúdo para IA  
- Criação de índices inteligentes  
- Exploração prática dos dados organizados

## 🎯 Objetivos de Aprendizagem

Ao final deste desafio, fui capaz de:

- Aplicar conceitos de IA em um ambiente prático com Azure  
- Documentar tecnicamente as etapas de forma estruturada  
- Utilizar o GitHub para compartilhar e versionar meu projeto  

## ✅ Entrega

Este repositório contém:

- `README.md` principal com visão geral do desafio e objetivos
- - Três pastas principais documentando cada etapa prática:
  - `01-ingestao-conteudo`: Ingestão de documentos no Azure Blob Storage
  - `02-criacao-indices`: Criação do índice e enriquecimento com Azure AI
  - `03-exploracao-dados`: Testes e consultas sobre os dados indexados

## 📎 Recursos Úteis

- [Explore an Azure AI Search index (UI)](https://learn.microsoft.com/en-us/training/modules/explore-azure-ai-search/)

---

> ⚠️ **Aviso de Segurança:** Durante os testes, o acesso anônimo ao container do Azure Blob foi habilitado para facilitar os testes. Essa prática **não deve ser aplicada em ambientes de produção**.
