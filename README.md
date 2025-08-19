#Análise de Vendas - Superstore 📈
Visão Geral do Projeto
Este projeto consiste na criação de um dashboard interativo no Power BI para analisar o desempenho de vendas da "Superstore", uma empresa fictícia de varejo. O objetivo é fornecer uma ferramenta de Business Intelligence que permita a exploração de dados e a identificação de tendências, sazonalidades e insights sobre o faturamento, produtos e clientes.

Veja o Dashboard Interativo aqui![https://app.powerbi.com/links/YPr6q0uGI8?ctid=9429526c-cbfb-4313-b93c-e286f9c80274&pbi_source=linkShare&bookmarkGuid=f86b4e70-59eb-4c99-8b1d-2a48090946d6]

Demonstração da Interatividade
Ferramentas Utilizadas
Power BI: Ferramenta principal para ETL, modelagem e visualização de dados.

Power Query (Editor M): Utilizado para todo o processo de extração, transformação e limpeza dos dados.

DAX (Data Analysis Expressions): Utilizado para a criação de medidas e colunas calculadas.

Etapas do Projeto
Extração e Carregamento de Dados: Os dados foram extraídos de um arquivo CSV (dataset público "Superstore").

Tratamento e Limpeza (ETL): Utilizando o Power Query, foram realizados os seguintes tratamentos:

Verificação e correção de tipos de dados.

Tradução de colunas e valores para o português (ex: Category, Region, Segment).

Criação de uma tabela calendário dinâmica com a linguagem M para suportar análises temporais.

Modelagem de Dados: Criação de um relacionamento entre a tabela fato (vendas) e a dimensão (calendário) para garantir a correta filtragem e análise de datas.

Criação de Medidas DAX: Desenvolvimento de medidas essenciais, como [Faturamento Total], para permitir análises dinâmicas.

Visualização de Dados: Construção do dashboard com visuais interativos, incluindo:

Matriz de faturamento mensal por ano com formatação condicional.

Gráfico de colunas para comparação anual.

Segmentadores de dados (filtros) por Região, Categoria e Segmento.

Principais Insights
Sazonalidade: Observa-se um pico consistente de vendas nos meses de Setembro e Novembro ao longo dos anos.

Crescimento Anual: O faturamento total demonstra um crescimento consistente ano após ano.

Desempenho por Categoria: A categoria de Tecnologia, apesar de ter menos pedidos, representa uma fatia significativa do faturamento.

Contato
Luiz Carlos Figueiredo Cabral

LinkedIn[https://www.linkedin.com/in/figueiredo-luiz]

Email: figueiredocabralluizcarlos@gmail.com
