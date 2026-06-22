# Projeto de Conclusão Análise de dados Grupo 2
Tema: Inteligência de Mercado Automotivo - Market Share e Evolução da Frota
Alunos: Diana, Douglas, Duda, Taynara, Thais e Will.

O Problema de Negócio
O setor automotivo brasileiro vive um momento de transformação histórica: a transição dos populares para os SUVs, a eletrificação da frota e a chegada agressiva de novas marcas asiáticas. As montadoras precisam de visibilidade total sobre o comportamento do mercado para guiar suas estratégias de vendas e produção. Seu desafio é estruturar um painel de inteligência competitiva que analise o histórico de emplacamentos por marca, modelo e categoria. O objetivo é cruzar essas vendas com o cenário econômico do país, entregando para a diretoria comercial um mapeamento claro de quem está ganhando e perdendo. 

Visão Geral do Projeto
O Dashboard Emplacamentos de Veículos e Impactos Econômicos é uma solução de inteligência de negócios desenvolvida para analisar o mercado automotivo brasileiro e correlacionar o desempenho de vendas e faturamento com os principais indicadores macroeconômicos (especificamente a taxa Selic).
O objetivo principal é transformar dados brutos de emplacamentos em insights estratégicos para montadoras, concessionárias e analistas de mercado, permitindo entender o comportamento do consumidor diante das flutuações econômicas ao longo dos anos (2020 a 2025).

Documentação do Projeto: Etapas de Desenvolvimento
Esta documentação detalha o ciclo de vida do projeto, desde a concepção e organização da equipe até a entrega final, destacando as metodologias, ferramentas e estratégias utilizadas para garantir a eficiência e a qualidade do trabalho.

1. Planejamento, Alinhamento e Gestão de Equipe
O projeto iniciou-se com uma leitura coletiva do tema proposto para garantir o alinhamento de todos os integrantes. Na sequência, foi elaborado um cronograma estratégico de divisão de tarefas baseado em dois pilares fundamentais:

Aproveitamento de Competências: As atividades foram delegadas de acordo com as principais habilidades técnicas de cada membro.

Afinidade Pessoal: Respeitou-se a preferência individual por determinadas áreas do projeto.

Resultado: Essa abordagem otimizou a curva de aprendizado, reduziu a complexidade das tarefas e resultou em uma execução consideravelmente mais ágil e harmônica.

2. Processo de ETL (Extração, Transformação e Carga)
Diante da escassez e da inconsistência de registros na base de dados sugerida inicialmente, a equipe adotou uma postura proativa para enriquecer o repositório do projeto:

Extração (E): Buscamos fontes alternativas e complementares de dados. Fonte de dados: Emplacamentos de veículos e marcas no Brasil - AUTOO . Para acelerar o processo de coleta, integramos ferramentas de Inteligência Artificial, otimizando drasticamente o tempo de captura das informações.

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

Arquitetura e Estrutura do Dashboard
   
1. Visão Geral do Projeto 
O Dashboard Emplacamentos de Veículos e Impactos Econômicos é uma ferramenta de inteligência de mercado projetada para analisar o comportamento do setor automotivo brasileiro no período de 2020 a 2025. O principal diferencial do relatório é o cruzamento de métricas internas de vendas (volume de emplacamentos, faturamento e market share por marca/modelo) com variáveis macroeconômicas (evolução da Taxa Selic), permitindo identificar padrões de consumo e a resiliência do mercado diante de políticas monetárias restritivas.

2. Arquitetura e Estrutura das Páginas
O relatório está dividido em duas visões complementares (telas), otimizadas para leitura do nível estratégico ao tático.

Tela 1: Indicadores Macroeconômicos e Market Share

Esta tela contextualiza o desempenho financeiro e de volume contra o cenário macroeconômico global do período.

Cards de Indicadores Chave (KPIs Superiores):
Faturamento Médio (R$ 1,45 Tri): Receita total estimada movimentada pelo setor de novos emplacamentos ao longo do período histórico monitorado.

Unidades Vendidas (11,7 Mi): Volume consolidado de veículos emplacados.

Ticket Médio (R$ 123,4 Mil): Valor médio gasto por veículo comercializado no país.

Média da Selic (9,72%): Média ponderada da taxa básica de juros da economia no intervalo de anos coberto.

Componentes Visuais (Gráficos):
O Impacto dos Juros (Selic) na Intenção de Compra de Veículos: Gráfico combinado (Barras + Linha). Apresenta a evolução anual do faturamento (barras azuis) e a taxa de juros Selic média por ano (linha azul escura). Mostra o faturamento subindo de R$ 186,3 Bi em 2020 para R$ 290,2 Bi em 2025, apesar da escalada da Selic de 2,81% para 13,96%.

Participação de Mercado (Market Share): Gráfico de Treemap estruturado por faturamento de marcas. Evidencia a liderança do ecossistema das seguintes montadoras:

Fiat: R$ 281 Bi

Volkswagen: R$ 215 Bi

Chevrolet: R$ 209 Bi

Toyota: R$ 194 Bi

Concentração de Vendas (Desempenho por Modelo): Gráfico de Dispersão (Bubble Chart) que cruza o preço médio de tabela FIPE (Eixo X) com o volume absoluto de unidades vendidas (Eixo Y), mapeando a densidade de modelos no mercado e destacando outliers de grande volume ou preço elevado.

Tela 2: Desempenho por Modelo e Filtros de Negócio

Esta página provê visões analíticas específicas por modelo de veículo e permite interações temporais diretas.

Componentes de Controle Interativo:
Segmentação de Ano (Slicer Superior): Filtros em botões para seleção de anos individuais (2020, 2021, 2022, 2023, 2024, 2025) para recalcular dinamicamente os rankings e insights.

Componentes Visuais (Gráficos):
Líderes de Vendas (Unidades Emplacadas por Veículo): Gráfico de barras horizontais indicando o top 5 de volume de emplacamentos.

Líder isolado: Fiat Strada (709,8 Mil unidades), seguido por Chevrolet Onix (573,7 Mil), Hyundai HB20 (540,2 Mil), Fiat Argo (475,1 Mil) e Volkswagen T-Cross (436,9 Mil).

Geração de Receita por Modelo de Veículo: Gráfico de barras horizontais focado no retorno financeiro gerado. Revela uma mudança de comportamento: embora a Fiat Strada lidere também em faturamento (R$ 78 Bi), modelos comerciais e SUVs mais caros, como a Toyota Hilux (R$ 71 Bi) e o Jeep Compass (R$ 66 Bi), sobem posições cruciais devido ao alto valor agregado do ticket.

Desempenho Financeiro por Segmento de Mercado: Área dedicada para análise da evolução percentual das categorias (ex: Hatch, Sedan, SUV, Picape).

3. Inteligência de Negócio & Insights Extraídos
O dashboard inclui uma seção automatizada de Storytelling/Insights de negócios na segunda tela, sintetizando as seguintes descobertas:

Premiumização e Mudança de Categoria: Entre 2020 e 2025, os segmentos tradicionais de entrada (como Hatch e Sedan) sofreram forte compressão de mercado. Em contrapartida, as categorias de SUVs e Picapes expandiram agressivamente. Conclui-se que o consumidor brasileiro migrou o perfil de compra para veículos de maior valor de tabela.

A Força do Consumidor de Alta Renda: O mercado demonstrou um comportamento contra-cíclico. Mesmo com a taxa Selic saltando de 2,81% em 2020 para 13,96% em 2025, o faturamento estimado cresceu continuamente. Isso comprova que as vendas tornaram-se altamente dependentes do público de alta renda, cuja decisão de compra é menos sensível a taxas de juros de financiamentos populares e bancários.

Entre 2020 e 2025, as fatias de carros tradicionais (como Hatch e Sedan) ficaram espremidas, enquanto o segmento de SUVs (em roxo) e Picapes explodiu. O consumidor brasileiro passou a comprar carros mais caros.

Mesmo com a Selic saltando de 2,81% em 2020 para 13,96% em 2025, o faturamento estimado cresceu continuamente. Isso indica que: O mercado tornou-se mais dependente de compradores de alta renda (que compram SUVs/Picapes e dependem menos de financiamento bancário comum).

Três marcas (Fiat com 281 Bi, Volkswagen com 215 Bi e Chevrolet com 209 Bi) dominam a maior parte do bolo financeiro dos emplacamentos. Elas conseguem equilibrar um portfólio que transita entre o carro de entrada (volume) e SUVs comerciais (margem).

A Taxa Selic não influencia tanto nas vendas de Luxo. Foi analisado que quanto maior a taxa Selic maior a queda de vendas populares enquanto categorias de maior valor agregado, como SUVs e Picapes, mantêm-se estáveis ou crescem gradativamente.


Aplicação Web

AUTOCOMPARA — Compare. Decida. Dirija. 

O AUTOCOMPARA é uma plataforma digital inteligente voltada ao consumidor final e a analistas de mercado, projetada para simplificar a jornada de escolha e compra de automóveis. A aplicação resolve a dor da fragmentação de informações no setor automotivo, centralizando especificações técnicas, preços (tabela FIPE), dados de mercado e histórico de vendas em um único ambiente comparativo e altamente visual. 

O site utiliza uma planilha online como fonte de dados. Assim, quando uma informação é atualizada, ela aparece automaticamente no sistema, garantindo que os usuários consultem dados mais recentes e confiáveis.


Comparação inteligente dos veículos

Ao selecionar os carros desejados, o sistema analisa diversos fatores importantes, como preço, consumo de combustível, custos de manutenção, segurança, espaço interno e valorização no mercado.

Com base nesses critérios, cada veículo recebe uma pontuação que ajuda o usuário a identificar qual opção oferece o melhor custo-benefício dentro da comparação realizada.

Busca por categoria

Para facilitar a navegação, os veículos são organizados por categorias, como Hatch, SUV, Sedan, Picape, Minivan e Furgão.

Isso permite que o usuário encontre mais rapidamente os modelos que atendem às suas necessidades, sem perder as opções que já havia selecionado anteriormente.

Apresentação da equipe

A plataforma também conta com uma área dedicada aos integrantes do projeto. Ao clicar na foto de um membro da equipe, o visitante pode acessar diretamente seu perfil profissional no LinkedIn e conhecer mais sobre sua trajetória.

Experiência moderna e agradável

O AUTOCOMPARA foi desenvolvido com foco na experiência do usuário, oferecendo uma interface moderna, organizada e fácil de usar em computadores, tablets e celulares.






