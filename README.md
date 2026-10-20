# analise_de_vendas_de_calcados
Inteligência de Estoque e Comportamento de Compra no Varejo de Calçados
📌 Visão Geral do Projeto
No varejo de calçados, o estoque parado representa capital de giro retido e perda de margem operacional[cite: 1]. Este projeto de Análise Exploratória e de Negócios utiliza dados transacionais de uma loja de calçados ao longo de um ano (200 vendas) para transformar dados brutos de frente de caixa em decisões estratégicas de compras, marketing e gestão financeira[cite: 1, 6].

A análise abrange desde o mapeamento da curva de numerações até a sazonalidade de coleções, identificação de compras casadas (cross-selling) e a consolidação de uma Demonstração do Resultado do Exercício (DRE)[cite: 1, 4, 5, 6].

Perguntas de Negócio (O "Porquê")
O projeto foi construído para responder a três dores estratégicas do gerenciamento da loja[cite: 1]:

Gestão de Grade e Estoque: Quais tamanhos e categorias estão prendendo capital na prateleira (encalhados) e quais esgotam rapidamente, gerando perda de vendas por falta de produto[cite: 1]?

Sazonalidade e Timing: Qual é o momento exato do ano para realizar a transição de vitrine (substituição de sandálias por botas de outono/inverno)[cite: 1]?

Ticket Médio e Venda Cruzada: Qual é o comportamento de compra combinada no balcão e quais produtos são mais frequentemente adquiridos juntos no mesmo recibo[cite: 1, 5]?

🛠️ Tecnologias e Ferramentas Utilizadas
Linguagem: Python 3.x

Manipulação e Análise de Dados: pandas, numpy

Visualização de Dados: matplotlib

Metodologia: Feature Engineering, Análise de Cesta de Compras, Curva de Distribuição e DRE Financeira[cite: 1, 5, 6]

📊 Principais Insights e Resultados
1. Curva de Tamanhos e Risco de Encalhe
Ao agrupar as vendas por numeração, a análise revelou uma distribuição em curva de sino[cite: 1]:

Tamanhos Centrais (37, 38 e 39): Concentram a imensa maioria do volume de vendas[cite: 1].

Tamanhos Extremos (34, 35, 43 e 44): Apresentam giro quase nulo, representando risco de capital retido[cite: 1].

Ação: Substituição imediata de compras em "grade fechada" por "grade aberta", concentrando o orçamento nos tamanhos 37 a 39[cite: 1].

2. Sazonalidade e Troca de Vitrine
A análise da evolução temporal mês a mês mostrou[cite: 4]:

A venda de Sandálias atinge seu declínio acelerado a partir de abril, enquanto a procura por Botas de Couro e Tênis tem seu pico de transição exatamente no mês de Abril[cite: 4].

Ação: Redefinição do calendário comercial: liquidação de verão em março e exposição da coleção de outono/inverno no início de abril[cite: 4].

3. Análise de Cesta de Compras (Cross-Selling)
De 104 faturas emitidas no ano, 60 contiveram 2 ou mais produtos (taxa de conversão conjunta de 57,7%)[cite: 5].

Combinação Campeã: Sapato Social + Tênis Esportivo liderou com 9 ocorrências no mesmo recibo[cite: 5].

Ação: Treinamento da equipe de vendas para oferta cruzada (desconto progressivo no segundo par de tênis ao adquirir sapato social)[cite: 5].
