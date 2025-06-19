# IA-para-gerar-insights-e-organizar-planilhas-de-dados

# 🚀 Análise de Vendas com IA | Desafio de Projeto

![License](https://img.shields.io/badge/license-MIT-blue.svg)

Este repositório documenta a solução completa de um desafio de projeto onde uma Inteligência Artificial (Gemini) foi utilizada para executar um pipeline de análise de dados, desde a limpeza e consolidação de fontes brutas até a extração de insights estratégicos para a empresa fictícia "Meganium".

## 💻 Sobre o Projeto

O objetivo foi simular um cenário real de análise de dados, onde a interação com uma ferramenta de IA transformou dados de vendas brutos e descentralizados em uma base de conhecimento coesa e acionável. O projeto demonstra um fluxo de trabalho iterativo, no qual os requisitos foram sendo refinados, e o processo de tratamento de dados foi aprimorado para garantir a máxima qualidade e precisão nos resultados.

### 🗺️ Navegação

* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Estrutura do Repositório](#estrutura-do-repositório)
* [Processo de Análise: Passo a Passo](#processo-de-análise-passo-a-passo)
* [Recomendações Estratégicas](#recomendações-estratégicas)
* [Como Utilizar o Projeto](#como-utilizar-o-projeto)
* [Licença](#licença)

### 🛠️ Tecnologias Utilizadas

* **Linguagem de Programação:** Python
* **Bibliotecas:** Pandas
* **Ferramenta de IA:** Google Gemini
* **Plataforma:** GitHub

### 📊 Processo de Análise: Passo a Passo

A análise foi conduzida através de uma série de prompts, evoluindo de uma simples solicitação para um processo de tratamento de dados mais robusto e detalhado.

#### Etapa 1: Solicitação Inicial e Primeira Análise
* **Prompt:** "Consolidar todas as bases de terceiros para realizar uma análise. Transformar dados de vendas em informações relevantes para a fabricante. Quais são os produtos mais populares em cada país? Como otimizar o processo de transporte e logística até o momento da venda?"
* **Ação da IA:** A IA unificou os três arquivos CSV e realizou uma análise preliminar.

#### Etapa 2: Aprimoramento e Refinamento do Processo
* **Prompts:** "mude o formato de date para o brasileiro", "transforme a birth date também".
* **Evolução do Processo:** O fluxo de trabalho foi revisado para criar um pipeline de limpeza mais completo e robusto.

#### Etapa 3: Pipeline de Limpeza e Formatação Profunda (Versão Final)
* **Prompts:** "para os tres arquivos csv que te mandei, corrija as datas para o formato brasileiro também, após isso, integre-os ao ultimo comando que te dei" e "formate os arquivos csv para que todos fiquem organizados, caso tenha algum erro de formatação".
* **Ação da IA (Workflow Refinado):**
    1.  **Limpeza na Fonte:** A IA processou cada um dos três arquivos de dados brutos individualmente.
    2.  **Formatação Abrangente:** Em cada arquivo, foram aplicadas as seguintes correções: padronização de nomes de colunas, formatação de datas para `DD/MM/AAAA`, remoção de espaços em branco e garantia de tipos de dados numéricos.
    3.  **Consolidação Final:** Após a limpeza individual, os três arquivos processados foram unificados no arquivo `Consolidated_Sales_Data_Final.csv`.

#### Etapa 4: Análise Demográfica
* **Prompt:** "mostre a idade média de cada país".
* **Ação da IA:** Utilizando o arquivo consolidado e limpo, a IA calculou a idade de cada comprador e agrupou os dados por país para extrair a média.

### ✨ Recomendações Estratégicas

1.  **Otimização Logística:** Os maiores volumes de venda estão concentrados no **Canadá** e na **França**. Recomenda-se priorizar a otimização logística nessas regiões.
2.  **Marketing Direcionado:** As campanhas devem ser segmentadas por país, considerando a popularidade dos produtos e o perfil demográfico (idade) dos clientes.
3.  **Gestão de Estoque Inteligente:** O estoque de produtos deve ser alocado geograficamente com base nos dados de popularidade para otimizar o inventário.

### 🚀 Como Utilizar o Projeto

1.  **Clone o repositório.**
2.  **Explore os dados:** Os dados brutos e processados estão na pasta `/data`.
3.  **(Opcional) Execute a análise:** Se um notebook for incluído, instale as dependências (`pandas`, `jupyter`) e execute-o.
