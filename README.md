# Projeto de Conclusão Análise de dados Grupo 2
Tema: Inteligência de Mercado Automotivo - Market Share e Evolução da Frota
Alunos: Diana, Douglas, Duda, Taynara, Thais e Will.

1. Visão Geral do Projeto
O Dashboard Emplacamentos de Veículos e Impactos Econômicos é uma solução de inteligência de negócios desenvolvida para analisar o mercado automotivo brasileiro e correlacionar o desempenho de vendas e faturamento com os principais indicadores macroeconômicos (especificamente a taxa Selic).
O objetivo principal é transformar dados brutos de emplacamentos em insights estratégicos para montadoras, concessionárias e analistas de mercado, permitindo entender o comportamento do consumidor diante das flutuações econômicas ao longo dos anos (2020 a 2025).

3. Arquitetura e Estrutura do Dashboard
O painel foi desenhado com uma interface moderna em modo escuro (dark mode) na barra lateral e áreas de dados em cartões flutuantes claros, priorizando a escalabilidade e a experiência do usuário (UI/UX).
2.1. Filtros e Navegação (Barra Lateral)
Menu de Navegação: Alternância entre visões estratégicas (atualmente na aba Visão Executiva, com suporte planejado para Performance de Produtos).
Filtros Temporais: Seleção multi escolha por anos de análise: 2020, 2021, 2022, 2023, 2024 e 2025.
Filtros Segmentados: Menus suspensos (dropdowns) para segmentação por Marca e Categoria do veículo.
2.2. Indicadores Chave de Desempenho (KPIs)
Posicionados no topo do painel para visualização imediata da saúde do mercado:
Faturamento Médio: R$ 1,45 Tri
Unidades Vendidas: 11,7 Mi
Ticket Médio: R$ 123,4 Mil
Média da Selic: 9,72%

5. Análises Visuais e Gráficos
📊 O Impacto dos Juros (Selic) na Intenção de Compra de Veículos
Tipo de Gráfico: Gráfico de combinação (Colunas e Linhas).
Eixo X: Linha do tempo anual (2020 - 2025).
Variáveis:
Colunas (Azul): Faturamento Médio por ano (ex: R$ 186,3 Bi em 2020 evoluindo para R$ 290,2 Bi em 2025).
Linha (Azul Escuro): Média da Selic (% a.a.), demonstrando a correlação direta entre o aumento dos juros e o comportamento do faturamento.
🗺️ Participação de Mercado (Market Share)
Tipo de Gráfico: Treemap (Mapa de Árvore).
Objetivo: Identificar rapidamente a dominância das marcas no setor automotivo por faturamento acumulado.
Destaques Visuais: Fiat (281 Bi) e Volkswagen (215 Bi) liderando o volume visual, seguidos por Chevrolet (209 Bi) e Toyota (194 Bi).
🎯 Concentração de Vendas: Desempenho por Modelo
Tipo de Gráfico: Gráfico de Dispersão (Scatter Plot).
Eixos:
Eixo Y: Unidades Vendidas (Volume).
Eixo X: Média de Preço Médio FIPE (R$) (Preço).
Legenda/Cores: Segmentação por marcas (BYD, CAOA, Chevrolet, Citroën, Fiat, Ford, GWM, entre outras).
Insight Gerado: Permite analisar o posicionamento de preço versus o volume de vendas de cada modelo, identificando outliers de mercado (modelos muito caros com baixo volume vs. modelos populares de alto giro).


