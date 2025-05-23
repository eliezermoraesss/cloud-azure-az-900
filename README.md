# 📘 Guia de Estudos: Certificação AZ-900 (Microsoft Azure Fundamentals)

Este repositório contém um resumo dos tópicos essenciais para a prova **AZ-900: Microsoft Azure Fundamentals**. Ideal para quem está começando no mundo da nuvem e deseja obter a certificação oficial da Microsoft.

---

## 📑 Sumário

- [📘 Guia de Estudos: Certificação AZ-900 (Microsoft Azure Fundamentals)](#-guia-de-estudos-certificação-az-900-microsoft-azure-fundamentals)
  - [📑 Sumário](#-sumário)
  - [📌 Estrutura do Estudo](#-estrutura-do-estudo)
    - [✅ 1. **Conceitos de Nuvem (15–20%)**](#-1-conceitos-de-nuvem-1520)
    - [✅ 2. **Serviços Principais do Azure (30–35%)**](#-2-serviços-principais-do-azure-3035)
    - [✅ 3. **Segurança, Conformidade e Identidade (25–30%)**](#-3-segurança-conformidade-e-identidade-2530)
    - [✅ 4. **Governança e Gerenciamento de Recursos (10–15%)**](#-4-governança-e-gerenciamento-de-recursos-1015)
    - [✅ 5. **Modelos de Preço e SLA (10–15%)**](#-5-modelos-de-preço-e-sla-1015)
  - [🛠️ Ferramentas Recomendadas](#️-ferramentas-recomendadas)
  - [🎯 Dicas para a Prova](#-dicas-para-a-prova)
  - [📚 Recursos Extras](#-recursos-extras)
    - [🚀 Criando Máquinas Virtuais no Azure](#-criando-máquinas-virtuais-no-azure)
    - [🗄️ Configurando uma Instância de Banco de Dados na Azure](#️-configurando-uma-instância-de-banco-de-dados-na-azure)
  - [🧱 Como Criar um Grupo de Recursos no Azure](#-como-criar-um-grupo-de-recursos-no-azure)
    - [✅ Criar via Portal Azure](#-criar-via-portal-azure)
    - [✅ Criar via Azure CLI](#-criar-via-azure-cli)
    - [✅ Criar via PowerShell](#-criar-via-powershell)
    - [⚙️ Configurando Recursos e Dimensionamentos em Máquinas Virtuais no Azure (Linux)](#️-configurando-recursos-e-dimensionamentos-em-máquinas-virtuais-no-azure-linux)
      - [✅ Passo a Passo pelo Portal Azure](#-passo-a-passo-pelo-portal-azure)
      - [📄 Documentação oficial](#-documentação-oficial)
    - [🤖 Utilizando Azure Cognitive Search: Indexação e Consulta de Dados com AI Search](#-utilizando-azure-cognitive-search-indexação-e-consulta-de-dados-com-ai-search)
      - [✅ Passo a Passo para Criar e Usar o Azure Cognitive Search](#-passo-a-passo-para-criar-e-usar-o-azure-cognitive-search)
      - [📄 Documentação oficial](#-documentação-oficial-1)
    - [🧠 Análise de Sentimentos com Language Studio no Azure AI](#-análise-de-sentimentos-com-language-studio-no-azure-ai)
      - [✅ Passo a Passo para Análise de Sentimentos](#-passo-a-passo-para-análise-de-sentimentos)
      - [📄 Documentação oficial](#-documentação-oficial-2)
    - [🤖 Explorando os Recursos de IA Generativa com Copilot e OpenAI](#-explorando-os-recursos-de-ia-generativa-com-copilot-e-openai)
      - [✅ Passo a Passo para Explorar IA Generativa no Azure](#-passo-a-passo-para-explorar-ia-generativa-no-azure)
      - [📄 Documentação oficial](#-documentação-oficial-3)

---

## 📌 Estrutura do Estudo

### ✅ 1. **Conceitos de Nuvem (15–20%)**

- Definição de Cloud Computing
- Modelos de Serviço:
  - IaaS (Infraestrutura como Serviço)
  - PaaS (Plataforma como Serviço)
  - SaaS (Software como Serviço)
- Tipos de Nuvem:
  - Nuvem Pública
  - Nuvem Privada
  - Nuvem Híbrida
- Benefícios da nuvem (alta disponibilidade, escalabilidade, agilidade, economia de custos, etc.)
- CapEx vs OpEx (Capital vs Operational Expenditure)

---

### ✅ 2. **Serviços Principais do Azure (30–35%)**

- Regiões, Zonas de Disponibilidade e Pares de Regiões
- Recursos e Grupos de Recursos
- **Serviços de Computação**:
  - Azure Virtual Machines (VMs)
  - Azure App Services
  - Containers (AKS, ACI)
  - Azure Functions
- **Serviços de Rede**:
  - Azure Virtual Network (VNet)
  - Load Balancer
  - VPN Gateway
  - ExpressRoute
  - Azure DNS
- **Serviços de Armazenamento**:
  - Azure Blob Storage
  - Azure Disk Storage
  - Azure File Share
  - Armazenamento de filas
- **Serviços de Banco de Dados**:
  - Azure SQL Database
  - Cosmos DB
  - Azure Database for MySQL/PostgreSQL

---

### ✅ 3. **Segurança, Conformidade e Identidade (25–30%)**

- Conceito de segurança na nuvem
- **Azure Security Center**
- **Azure Defender (Microsoft Defender for Cloud)**
- **Azure Network Security Groups (NSG)**
- **Azure Firewall**
- **Azure DDoS Protection**
- Autenticação e Autorização:
  - Azure Active Directory (Azure AD)
  - Multi-Factor Authentication (MFA)
  - Role-Based Access Control (RBAC)
- **Conformidade**:
  - Microsoft Trust Center
  - Azure Compliance Documentation

---

### ✅ 4. **Governança e Gerenciamento de Recursos (10–15%)**

- Azure Resource Manager (ARM)
- Azure Management Tools:
  - Azure Portal
  - Azure CLI
  - Azure PowerShell
- Azure Policy
- Azure Blueprints
- Controle de Custos:
  - Azure Cost Management
  - Azure Pricing Calculator
  - Azure TCO Calculator
- Etiquetas (Tags) e Locks

---

### ✅ 5. **Modelos de Preço e SLA (10–15%)**

- Preço baseado em consumo
- Zonas e camadas de preços
- Calculadoras de custos
- Contrato de Nível de Serviço (SLA)
- Disponibilidade e Resiliência
- Ciclo de vida dos serviços Azure

---

## 🛠️ Ferramentas Recomendadas

- [Portal Azure](https://portal.azure.com)
- [Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/)
- [Microsoft Learn – AZ-900](https://learn.microsoft.com/en-us/certifications/azure-fundamentals/)
- [Exam Skills Outline (PDF Oficial)](https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RW110ZBP)

---

## 🎯 Dicas para a Prova

- Foque na **compreensão dos conceitos**, mais do que na prática técnica.
- Use **flashcards** para memorizar termos importantes.
- Pratique com **simulados** gratuitos online.
- Acompanhe vídeos explicativos no YouTube e no Microsoft Learn.

---

## 📚 Recursos Extras

- [Curso Gratuito da Microsoft Learn](https://learn.microsoft.com/training/paths/azure-fundamentals/)
- [Canal no YouTube – AZ-900 em português](https://www.youtube.com/results?search_query=AZ-900+em+português)
- [Simulados AZ-900 (Whizlabs, ExamTopics, etc.)](https://www.examtopics.com/exams/microsoft/az-900/)

---

### 🚀 Criando Máquinas Virtuais no Azure

- Guia oficial: [Criar uma máquina virtual no Azure Portal](https://learn.microsoft.com/pt-br/azure/virtual-machines/windows/quick-create-portal)
- Documentação geral: [Documentação de Máquinas Virtuais do Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/)

### 🗄️ Configurando uma Instância de Banco de Dados na Azure

- Guia oficial: [Criar uma instância de Banco de Dados SQL no Azure](https://learn.microsoft.com/pt-br/azure/azure-sql/database/single-database-create-quickstart)
- Documentação geral: [Documentação de Banco de Dados do Azure](https://learn.microsoft.com/pt-br/azure/azure-sql/)
-

---

## 🧱 Como Criar um Grupo de Recursos no Azure

Um **Grupo de Recursos** é um contêiner lógico onde você pode gerenciar recursos do Azure como VMs, bancos de dados, redes etc.

### ✅ Criar via Portal Azure

1. Acesse o [Portal do Azure](https://portal.azure.com)
2. No menu lateral, clique em **Grupos de recursos**
3. Clique em **+ Criar**
4. Preencha os campos:
   - Assinatura
   - Nome do grupo de recursos
   - Região
5. Clique em **Revisar + Criar** e depois em **Criar**

### ✅ Criar via Azure CLI

```bash
az group create --name MeuGrupoDeRecursos --location eastus
```

### ✅ Criar via PowerShell

```powershell
New-AzResourceGroup -Name "MeuGrupoDeRecursos" -Location "EastUS"
```

Use sempre nomes claros e padronizados para facilitar a organização.

---

### ⚙️ Configurando Recursos e Dimensionamentos em Máquinas Virtuais no Azure (Linux)

Veja como criar uma máquina virtual Linux do zero no Azure Portal:

#### ✅ Passo a Passo pelo Portal Azure

1. Acesse o [Portal do Azure](https://portal.azure.com)
2. No menu lateral, clique em **Máquinas Virtuais** e depois em **+ Criar**
3. Escolha **Máquina virtual do Azure**
4. Preencha os campos obrigatórios:
   - **Assinatura** e **Grupo de Recursos** (crie um novo se necessário)
   - **Nome da máquina virtual**
   - **Região** (ex: Brazil South, East US)
   - **Imagem**: selecione uma distribuição Linux (ex: Ubuntu Server 22.04 LTS)
   - **Tamanho**: clique em **Alterar tamanho** e escolha o dimensionamento (ex: Standard_B1s para testes)
   - **Usuário e senha/SSH**: defina o método de autenticação
5. Em **Discos**, escolha o tipo de disco (SSD ou HDD)
6. Em **Rede**, configure ou crie uma nova VNet e Sub-rede
7. Revise as configurações e clique em **Criar**

#### 📄 Documentação oficial

- [Criar uma VM Linux no Azure Portal](https://learn.microsoft.com/pt-br/azure/virtual-machines/linux/quick-create-portal)
- [Dimensionamento de VMs no Azure](https://learn.microsoft.com/pt-br/azure/virtual-machines/sizes)

---

### 🤖 Utilizando Azure Cognitive Search: Indexação e Consulta de Dados com AI Search

O **Azure Cognitive Search** permite criar experiências de busca inteligentes em seus dados, utilizando recursos de IA para análise de texto, imagens e mais.

#### ✅ Passo a Passo para Criar e Usar o Azure Cognitive Search

1. Acesse o [Portal do Azure](https://portal.azure.com)
2. No menu lateral, clique em **Criar um recurso** e pesquise por **Azure Cognitive Search**
3. Clique em **Criar** e preencha os campos obrigatórios:
   - **Nome do serviço**
   - **Assinatura** e **Grupo de Recursos**
   - **Localização** (ex: Brazil South)
   - **Camada de preço** (Free, Basic, Standard, etc.)
4. Clique em **Revisar + Criar** e depois em **Criar**
5. Após a implantação, acesse o serviço criado e clique em **Importar dados**
6. Escolha a fonte de dados (ex: Azure Blob Storage, SQL Database, etc.) e configure a conexão
7. Defina o **Index** (estrutura dos campos que serão pesquisáveis)
8. Configure o **Indexer** (responsável por ler e indexar os dados)
9. Finalize e aguarde a indexação dos dados
10. Utilize o **Explorador de Pesquisa** no portal para testar consultas ou utilize a **API REST** para integrar buscas em suas aplicações

#### 📄 Documentação oficial

- [Introdução ao Azure Cognitive Search](https://learn.microsoft.com/pt-br/azure/search/search-what-is-azure-search)
- [Quickstart: Criar um serviço e importar dados](https://learn.microsoft.com/pt-br/azure/search/search-create-service-portal)

---

### 🧠 Análise de Sentimentos com Language Studio no Azure AI

O **Language Studio** do Azure AI permite analisar sentimentos de textos em português e outros idiomas, utilizando inteligência artificial de forma simples e visual.

#### ✅ Passo a Passo para Análise de Sentimentos

1. Acesse o [Azure AI Language Studio](https://language.azure.com/)
2. Faça login com sua conta Microsoft/Azure.
3. No menu lateral, clique em **Análise de Sentimento**.
4. Escolha a opção **Experimentar** para testar sem criar recursos, ou clique em **Criar recurso** para usar em produção.
5. Insira o texto que deseja analisar (pode ser em português).
6. Clique em **Executar** para obter o resultado.
7. O Language Studio exibirá o sentimento detectado (positivo, negativo, neutro ou misto) e a pontuação de confiança.
8. Para uso em aplicações, utilize a **API REST** do Azure AI Language, criando um recurso de **Serviços Cognitivos** no Portal do Azure e obtendo a chave e endpoint.

#### 📄 Documentação oficial

- [Visão geral do Language Studio](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/language-studio)
- [Análise de Sentimento com Azure AI Language](https://learn.microsoft.com/pt-br/azure/ai-services/language-service/sentiment-opinion-mining/overview)

---

### 🤖 Explorando os Recursos de IA Generativa com Copilot e OpenAI

O Azure oferece integração com serviços de IA generativa, como o Azure OpenAI Service e o GitHub Copilot, permitindo criar, automatizar e potencializar aplicações com inteligência artificial avançada.

#### ✅ Passo a Passo para Explorar IA Generativa no Azure

1. **Acesse o Portal do Azure:**  
   Entre em [portal.azure.com](https://portal.azure.com).

2. **Crie um recurso do Azure OpenAI Service:**  
   - No menu lateral, clique em **Criar um recurso**.
   - Pesquise por **Azure OpenAI** e selecione o serviço.
   - Clique em **Criar** e preencha os campos obrigatórios (assinatura, grupo de recursos, região, nome do recurso).
   - Clique em **Revisar + Criar** e depois em **Criar**.

3. **Aguarde a implantação e acesse o recurso:**  
   - Após a criação, acesse o recurso do Azure OpenAI.
   - No painel do serviço, clique em **Playground** para testar modelos como GPT-4, GPT-3.5, DALL-E, etc.

4. **Teste prompts e gere textos ou imagens:**  
   - No Playground, selecione o modelo desejado (ex: GPT-4 para texto, DALL-E para imagens).
   - Insira um prompt (exemplo: "Explique o que é computação em nuvem").
   - Clique em **Enviar** para ver a resposta gerada pela IA.

5. **Integre a API OpenAI em suas aplicações:**  
   - No painel do recurso, acesse **Chaves e Endpoints** para obter as informações de acesso à API.
   - Utilize as credenciais em aplicações, scripts ou chatbots para consumir IA generativa via REST API.

6. **Utilize o GitHub Copilot para programação assistida:**  
   - Instale a extensão do GitHub Copilot no Visual Studio Code.
   - Faça login com sua conta GitHub.
   - Escreva comentários ou trechos de código e veja sugestões automáticas geradas pela IA.

#### 📄 Documentação oficial

- [Azure OpenAI Service – Visão geral](https://learn.microsoft.com/pt-br/azure/ai-services/openai/overview)
- [GitHub Copilot – Documentação](https://docs.github.com/pt/copilot)
- [Como usar o Playground do Azure OpenAI](https://learn.microsoft.com/pt-br/azure/ai-services/openai/quickstart)

---

Com fé em Deus e foco nos estudos, a aprovação virá! 🙌
