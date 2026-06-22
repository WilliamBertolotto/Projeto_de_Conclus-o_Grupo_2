# Projeto de Conclusão Análise de dados Grupo 2
Tema: Inteligência de Mercado Automotivo - Market Share e Evolução da Frota
Alunos: Diana, Douglas, Duda, Taynara, Thais e Will.

Documentação do Projeto: Etapas de Desenvolvimento
Esta documentação detalha o ciclo de vida do projeto, desde a concepção e organização da equipe até a entrega final, destacando as metodologias, ferramentas e estratégias utilizadas para garantir a eficiência e a qualidade do trabalho.

1. Planejamento, Alinhamento e Gestão de Equipe
O projeto iniciou-se com uma leitura coletiva do tema proposto para garantir o alinhamento de todos os integrantes. Na sequência, foi elaborado um cronograma estratégico de divisão de tarefas baseado em dois pilares fundamentais:

Aproveitamento de Competências: As atividades foram delegadas de acordo com as principais habilidades técnicas de cada membro.

Afinidade Pessoal: Respeitou-se a preferência individual por determinadas áreas do projeto.

Resultado: Essa abordagem otimizou a curva de aprendizado, reduziu a complexidade das tarefas e resultou em uma execução consideravelmente mais ágil e harmônica.

2. Processo de ETL (Extração, Transformação e Carga)
Diante da escassez e da inconsistência de registros na base de dados sugerida inicialmente, a equipe adotou uma postura proativa para enriquecer o repositório do projeto:

Extração (E): Buscamos fontes alternativas e complementares de dados. Para acelerar o processo de coleta, integramos ferramentas de Inteligência Artificial, otimizando drasticamente o tempo de captura das informações.

Tratamento e Transformação (T): A limpeza, padronização e consolidação dos dados coletados foram realizadas de forma híbrida, utilizando fórmulas avançadas no Microsoft Excel e consultas estruturadas no Google BigQuery.

3. Desenvolvimento de Dashboards (Visualização de Dados)
Com a base de dados consolidada, iniciamos a construção dos painéis visuais utilizando o Power BI, realizando o cruzamento de múltiplos bancos de dados e tabelas.

Para garantir a qualidade da entrega, a equipe realizou uma análise minuciosa conjunta guiada pelo princípio da clareza analítica:

Evitar a Poluição Visual: Filtragem rigorosa para que o excesso de dados não sobrecarregasse o leitor.

Evitar a Escassez de Dados: Garantia de que as métricas essenciais estivessem presentes para gerar insights de valor.

4. Desenvolvimento da Aplicação
Como solução prática do projeto, desenvolvemos uma plataforma online voltada para o consumidor final. O desenvolvimento do código foi acelerado e otimizado com o suporte de Inteligência Artificial.

Funcionalidade: A aplicação permite a comparação direta de diversos veículos em um único lugar, aplicando filtros por marca, modelo e categoria.

Valor Agregado: Auxilia o usuário a realizar uma compra consciente, centralizando informações que antes exigiriam buscas em múltiplos sites. Tudo isso aliado a uma interface de usuário (UI) moderna e atraente.

5. Storytelling e Apresentação dos Resultados
Na fase final, a equipe reuniu-se para estruturar a narrativa do projeto. O objetivo foi converter os dados técnicos em uma história fluida, linear e coesa:

Eliminação de ruídos e detalhes técnicos redundantes.

Inclusão de ganchos lógicos para garantir uma estrutura clara com início, meio e fim.

6. Revisão Geral e Garantia de Qualidade (QA)
Por fim, realizamos um processo de auditoria coletiva. Todo o grupo revisou o projeto de ponta a ponta, inspecionando códigos, dashboards, documentação e a aplicação para identificar e corrigir possíveis lacunas, erros de lógica ou inconsistências antes da entrega definitiva.

Dashboards interativos

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


