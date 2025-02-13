# Dashboard de Relatório Geral de Vendas

Desenvolvi um dashboard utilizando um banco de dados em CSV com o objetivo de definir os próximos passos estratégicos de vendas. Utilizei as informações disponíveis para estabelecer a estratégia da empresa para o próximo ano, focando no aumento de receita.


# Contexto

Como analista de dados, meu objetivo foi analisar vários aspectos de vendas, receita e lucro para avaliar o status do crescimento de dessa empreasa. A partir dessas análises, elaborei recomendações e planos de ação que orientarão a estratégia de crescimento da empresa.

# Plano de negocio 

=> contagem de vendas distintas;

		=> total da quantidade vendida;

		=> total do valor vendido (quantidade x preço unitário);

		=> total do custo das vendas (quantidade x custo unitário);

		=> valor médio dos preços unitários;

		=> total de desconto cedido nas vendas;

		=> o total de desconto, apenas para as promoções que estavam vigentes no momento da venda;

		=> vendas brutas sem os descontos (utilizar o [Desconto total] = medida f.);

		=> valor, em média, de vendas brutas por dia. Devem ser contabilizados apenas os dias em que houveram vendas.

	  => vendas brutas do ano anterior;

		=> diferença em percentual das vendas brutas entre o período atual e o mesmo período no ano anterior;

		=> vendas brutas acumuladas partindo do primeiro dia do ano até a data (mês ou dia) selecionada;

		=> vendas brutas do mesmo período no ano anterior, onde somam-se os valores do ano anterior apenas até a maior data de dados existentes do período atual. Exemplo: se a maior data de dados é 20/06/2022, deve-se somar o LY até 20/06/2021. 
	

		=> calcular o % representativo contra o total da Categoria (coluna dCategoriaProdutos[Categoria]). A medida deve retornar o mesmo valor para uma dada categoria, independente dos filtros externos aplicado na Categoria de produtos;

		=> calcular o % representativo contra o total, independente da segmentação que seja utilizada (ano, mês, categoria de produtos, lojas e etc...);

		=> calcular o % share por Continente e Categoria sempre totalizando 100% no nível selecionado, use o dLocalidades[Continente] agregando 		

		=> dCategoriaProdutos[Categoria] numa matriz (Continente > Categoria);	

		=> calcular o valor do ranking de cada uma das promoções, baseado nas maiores vendas líquidas. Ordem do ranking descendente;

		=> calcular a representatividade dos top 10 produtos em relação ao total de vendas brutas e segmentar no visual por cada um dos anos. Os top 10 produtos devem ser os top 10 de cada um dos anos da segmentação, ou seja, essa lista de produtos pode mudar de 2021 para 2022.


  # Desenvolvimento

 # 1. Cartões (Cards)
Resumo de métricas importantes, como total de vendas e total de lucro.
Funções usadas: Operações Matemáticas.

 # 2. Gráficos de Barras
Visualização das principais fontes de vendas, tipo de loja, produtos.
Funções usadas: Operações Matemáticas.

 # 3. Gráficos de Linhas
Gráfico de linhas mostrando a variação enter lucro e a vendas brutas ao longo do tempo.
Funções usadas: Função espcifica criada - Slicer_Grafico

 # 4. Integração no Dashboard
Organizei todas as visualizações e métricas em um único dashboard para facilitar a análise e a tomada de decisão pela equipe de negócios.

 # 5. Filtros 
Alem de filtros especificos criadas para atualizar graficos especificos, foi criado um filtro generico com uma maior ação, onde é possivel filtrar de forma mais ampla toda a visualização do dashboard.
Filtro criado pela "Seleção", ao clicar abre uma aba com segmentações menores. 

 # 6. Permissao de acesso
Cartão criado para identificar cada usuario que modifica o nome/login personalizado para cada usuario 


