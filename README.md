### 🧩 1. Contexto

Este projeto simula a análise de dados de vendas com o objetivo de compreender o desempenho das vendas no período de 2021 a 2024, o desempenho dos vendedores e as categorias mais vendidas.

### 🎯 2. Objetivo

Analisar os dados de vendas para identificar os períodos com melhor desempenho, padrões ao longo do tempo e oportunidades de melhoria nos resultados.

### 📁 3. Dataset

- Base com registros de vendas
- Período analisado: jan/2021 a abr/2024
- Principais campos: data, valor, quantidade, vendedor, categoria

### 🧹 4. Tratamento dos dados

- Padronização de nomes
- Ajuste de tipos de dados

## 📊 Gráficos e análises

Primeira pagina do dashboard

![Graficos bike store.](/Dash.png)

Aplicação do filtro de ranking de catégoria

![Graficos bike store.](/Dash%20filtro%20Categoria.png)

### 📈 Gráfico 1 – Top 3 Vendedores

**Pergunta:** Quais os 3 vendedores com maior desempenho ao longo dos anos?

**O que mostra:**
O valor de venda total efetuado por cada um dos 3 vendedores em destaque

**Insight:**
De acordo com os dados, podemos observar que grande parte do faturamento da empresa está concentrado nas vendas realizadas por esses 3 vendedores. Isso pode indicar que eles possuem uma experiencia maior do que as demais ou conhecimento em estrategia de vendas mais eficazes.

**Possível ação:**
Analisar os metodos de vendas adotados e como elas são aplicadas, com o objetivo de replica-las para os demais vendedores

### 📈 Gráfico 2 – Total de Vendas por Ano

**Pergunta:** Como as vendas se comportaram ao longo dos anos?

**O que mostra:**
Evolução do valor total de vendas somente até o ano de 2023, pois no ano seguinte mostra-se uma queda drastica no valor das vendas.

**Insight:**
As vendas apresentaram crescimento consistente entre 2021 e 2023, seguido de uma queda acentuada em 2024.

**Possível ação:**
Investigar fatores como mudanças no modo de locomoção dos consumidores, surgimento de empresas concorrentes, novos modelos de negocios e reforçar ações comerciais para os proximos períodos.

### 📈 Gráfico 3 – Ranking de vendas por vendedor e por categoria

**Pergunta:** Como o faturamento se distribui entre os vendedores e entre as categorias de produtos?

**O que mostra:**  
Visual interativo com filtro de seleção que permite analisar a distribuição do faturamento por vendedor ou por categoria, possibilitando a comparação entre os diferentes grupos.

**Insight:**  
Ao analisar o ranking de vendedores, é possível identificar diferentes níveis de desempenho, como vendedores com desempenho superior, mediano e inferior. Essa variação levanta questionamentos sobre os métodos de venda utilizados e sua relação com os resultados obtidos.  
No ranking por categoria, observa-se que a prestação de serviços é a mais rentável, seguida pela venda de componentes e, por último, pela venda de bicicletas, evidenciando o principal ponto forte da empresa.

**Possível ação:**  
Para melhorar o desempenho dos vendedores com resultados inferiores, pode-se investir em treinamentos, utilizando os vendedores de melhor desempenho como referência para compartilhamento de técnicas e boas práticas.  
Em relação às categorias, é interessante avaliar estratégias para impulsionar as vendas de bicicletas e componentes, bem como manter e aprimorar a qualidade da prestação de serviços.

### 📈 Gráfico 4 – Participação das Vendas por Categoria

**Pergunta:** Qual a participação de cada categoria no faturamento total?

**O que mostra:**  
Distribuição percentual do faturamento entre as categorias, evidenciando a representatividade de cada uma no total de vendas, conforme abordado anteriormente no gráfico de ranking.

### 📈 Gráfico 5 - Total de vendas por Cargo

**Pergunta:** Como o faturamento se distribui entre os vendedores de acordo com o cargo?

**O que mostra:**  
Ranking do valor total de vendas agrupado por cargo do vendedor. Observa-se que os maiores volumes de faturamento estão associados aos vendedores de nível sênior, seguidos pelos cargos pleno, júnior, assistente e estagiário.

**Insight:**  
Os dados sugerem uma relação entre o nível do cargo e o desempenho em vendas, indicando que cargos mais experientes tendem a apresentar maiores resultados.

**Possível ação:**  
Investir em treinamentos e capacitações para os cargos de menor nível, com o objetivo de desenvolver competências comerciais e preparar esses profissionais para níveis mais avançados.

### 📈 Gráfico 6 - Total de vendas por Ano e Mês

**Pergunta:** Como as vendas evoluíram ao longo dos meses em cada ano analisado?

**O que mostra:**  
Gráfico de área que apresenta a evolução do faturamento mensal ao longo dos anos, com destaque para os valores de vendas em cada período.

**Insight:**  
Em 2021, as vendas iniciaram em aproximadamente R$ 2,25 milhões em janeiro, apresentaram oscilações ao longo do ano e encerraram em torno de R$ 2,39 milhões.  
Em 2022, observa-se um pico expressivo de faturamento em janeiro, com aproximadamente R$ 7,3 milhões, seguido por uma tendência de queda ao longo do ano.  
Já em 2023, o faturamento iniciou em cerca de R$ 9,1 milhões, manteve uma tendência de decréscimo ao longo dos meses, com um novo pico observado em novembro, seguido de nova redução.  
Em 2024, os dados indicam um volume significativamente menor de vendas, com cerca de R$ 49 mil em janeiro e R$ 270,5 mil em abril, último mês analisado.

**Possível ação:**  
Investigar os fatores que influenciam os picos de vendas observados no início dos anos e em meses específicos, bem como compreender as causas da redução expressiva do faturamento em 2024, considerando aspectos como sazonalidade, mudanças operacionais ou disponibilidade de dados.

### Segunda pagina do Dashboard

Na segunda pagina é apresentado a tabela de dados utilizada, contendo filtros de vendedor, produto, categoria e cargo.

![Graficos bike store.](/Segunda%20pagina%20do%20Dashboard.png)

## 🧾 Conclusão

A análise dos dados de vendas no período de 2021 a 2024 permitiu identificar padrões relevantes de desempenho ao longo do tempo, bem como diferenças significativas entre vendedores, cargos e categorias de produtos. Observou-se crescimento consistente do faturamento até 2023, seguido por uma redução expressiva em 2024, o que destaca a importância de análises contínuas para compreensão do cenário de vendas.

Os resultados evidenciaram que a prestação de serviços representa a principal fonte de faturamento da empresa, enquanto as categorias de componentes e bicicletas apresentam menor participação, indicando oportunidades de diversificação da receita. Além disso, a análise por vendedor e por cargo mostrou concentração de resultados em profissionais mais experientes, reforçando a relevância de estratégias de capacitação e compartilhamento de boas práticas.

De forma geral, o dashboard desenvolvido facilita a visualização e interpretação dos dados, apoiando a tomada de decisão e permitindo identificar oportunidades de melhoria nos processos comerciais. Este projeto teve como objetivo aplicar, de forma prática, conceitos de análise de dados utilizando Excel e Power BI, contribuindo para o desenvolvimento de habilidades analíticas e de visualização de informações.
