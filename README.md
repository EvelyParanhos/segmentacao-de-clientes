### Segmentação de Clientes da Loja "O Mercado"

#### 🎯 Objetivo do Projeto

Este projeto tem como objetivo principal a **segmentação de clientes** da loja “O Mercado”, que enfrenta desafios em suas estratégias de marketing. Através da análise do comportamento de compra, o projeto busca identificar grupos de clientes com perfis distintos, permitindo à empresa otimizar suas campanhas e promover o crescimento sustentável.

A análise utiliza a metodologia **RFM (Recência, Frequência, Valor Monetário)** para classificar os clientes e oferece insights práticos para guiar decisões estratégicas e aumentar o retorno sobre o investimento em marketing.

---

#### 🛠️ Ferramentas e Tecnologias

* **Google Planilhas:** Utilizado para todo o processamento, limpeza, análise e segmentação dos dados.
* **Google Slides & Canva:** Ferramentas usadas para a criação de apresentações e dashboards visuais.

---

#### 📊 Metodologia e Processamento de Dados

A análise foi conduzida em cinco etapas principais, detalhadas abaixo:

1.  **Processamento e Preparação da Base de Dados:**
    * **Fonte de Dados:** Três conjuntos de dados cobrindo o período de 30/07/2020 a 31/12/2022, contendo informações sobre clientes, transações e resumo de compras.
    * **Integração:** Os dados foram importados para uma única planilha usando a função `IMPORTRANGE`.

2.  **Limpeza e Validação de Dados:**
    * **Valores Nulos:** Foram identificados e removidos valores nulos nas tabelas de clientes e transações usando a função `QUERY` para garantir a integridade da análise.
    * **Duplicatas:** Nove registros duplicados foram encontrados na tabela `resumo_compras` e removidos usando a função `UNIQUE`.
    * **Validação Cruzada:** Foi aplicada uma validação para garantir que os clientes estivessem presentes nas três bases de dados, filtrando apenas os registros aptos para a análise.

3.  **Unificação e Criação de Novas Variáveis:**
    * As três tabelas foram consolidadas em uma única aba, unindo os dados através do `id_cliente`.
    * Foram criadas novas variáveis, como `total_compras`, `faixa_etária` e `meses_transacoes`, para enriquecer a análise e permitir a segmentação.

4.  **Análise Exploratória de Dados (EDA):**
    * Foram criadas **tabelas dinâmicas** para agrupar e resumir dados de forma prática. Algumas análises-chave incluíram:
        * Total de clientes que responderam a campanhas de marketing.
        * Média salarial por faixa etária.
        * Total gasto por categoria de produto (vinho, carnes, etc.) por faixa etária.
        * Comparativo de transações entre loja física e online.
    * **Visualização:** Foram gerados gráficos de colunas, pizza e linhas para representar visualmente os principais insights, incluindo a distribuição dos clientes por faixa etária, estado civil, e o volume de transações por mês.

5.  **Aplicação da Técnica RFM e Segmentação:**
    * **Cálculo dos Quartis:** Foram calculados os quartis para as métricas de Recência (dias desde a última compra), Frequência (quantidade de compras) e Monetização (valor total gasto).
    * **Pontuação RFM:** As métricas numéricas foram convertidas em pontuações de 1 a 5, classificando cada cliente.
    * **Segmentação Final:** Os clientes foram classificados em grupos estratégicos como **Leais/Top**, **Potenciais**, **Em Risco** e **Dormindo/Perdidos**, permitindo uma abordagem de marketing personalizada.

---

#### 📈 Resultados e Recomendações de Negócio

A análise demonstrou que a loja pode ir além de campanhas genéricas e adotar um marketing orientado a dados. As principais descobertas incluem:

* **Baixa Taxa de Resposta a Campanhas:** Apenas 15% dos clientes responderam positivamente às campanhas, indicando a necessidade de segmentação.
* **Segmentação RFM:** Quase metade dos clientes se encontra nos grupos **Em Risco** ou **Dormindo/Perdidos**, mas há uma base sólida de clientes **Leais/Top** que deve ser valorizada.
* **Comportamento de Compra:** O **vinho** é o produto mais popular em todas as faixas etárias, e a **loja física** tem maior volume de vendas que a online.
* **Oportunidades de Crescimento:** O público jovem (18-30 anos), embora pequeno, é o mais engajado. Há oportunidades claras de reativar clientes inativos e aumentar o engajamento em meses de menor movimento.

Com base nesses insights, foram elaboradas recomendações estratégicas para a loja “O Mercado”, como:
* Criação de um **clube do vinho** ou combos promocionais.
* Campanhas de **reengajamento** personalizadas para clientes em risco.
* Estratégias de marketing em redes sociais para o público mais jovem.
* Implementação de um **programa VIP** para clientes leais.
* Otimização das campanhas de marketing com base no perfil RFM.

---

#### 🔗 Recursos Adicionais

* [Link para a apresentação em slides](https://www.exemplo.com/apresentacao-projeto1)
* [Link para o vídeo de apresentação](https://www.exemplo.com/video-projeto1)
