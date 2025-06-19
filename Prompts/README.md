# 📄 Jornada de Prompts: A Evolução de uma Análise de Dados

Este documento detalha a sequência de prompts de comando utilizados durante este chat para realizar uma análise de dados de vendas. A progressão dos prompts demonstra um fluxo de trabalho realista, que evoluiu de uma pergunta de negócio ampla para refinamentos técnicos específicos, resultando em um produto de dados robusto e bem documentado.

---

### Fase 1: A Pergunta de Negócio Inicial

Nesta fase, o objetivo era amplo: extrair valor de dados brutos.

* **Prompt Principal:**
    > "Consolidar todas as bases de terceiros para realizar uma análise. Transformar dados de vendas em informações relevantes para a fabricante. Quais são os produtos mais populares em cada país? Como otimizar o processo de transporte e logística até o momento da venda?"

* **O Objetivo:** Obter uma visão 360º do negócio a partir de múltiplas fontes de dados, focando em insights de produto e logística.

* **A Ação da IA:**
    1.  Consolidação dos dados de 3 planilhas.
    2.  Análise de popularidade de produtos por país.
    3.  Análise de volume de vendas por país para sugerir otimizações.

* **Evolução:** Este prompt inicial definiu o escopo do projeto e gerou os primeiros insights estratégicos.

---

### Fase 2: Refinamento e Qualidade dos Dados

Após a análise inicial, o foco mudou para a qualidade e legibilidade dos dados.

* **Prompts Sequenciais:**
    > 1. "mude o formato de date para o brasileiro"
    > 2. "transforme a birth date também"
    > 3. "mostre a idade média de cada país"

* **O Objetivo:** Padronizar os dados para o contexto local (Brasil) e extrair novas informações demográficas a partir dos dados já limpos.

* **A Ação da IA:**
    1.  Formatou as colunas de data para o padrão `DD/MM/AAAA`.
    2.  Calculou a idade de cada comprador e apresentou a média por país.

* **Evolução:** O projeto saiu da análise puramente de vendas para incluir a demografia dos clientes. A qualidade dos dados se tornou uma prioridade.

---

### Fase 3: Documentação e Estruturação do Projeto

Com a análise concluída, a necessidade passou a ser a de documentar o processo de forma profissional.

* **Prompts Principais:**
    > 1. "Descrição do Desafio... Este projeto tem como objetivo explorar o uso de prompts..."
    > 2. "se baseie neste formato de repositório" (com a imagem de um repositório GitHub)
    > 3. "faça um arquivo read.me detalhando
