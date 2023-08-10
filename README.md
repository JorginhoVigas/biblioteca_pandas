# biblioteca_pandas

#O dataset de varejo que temos em maos é composto por informacoes de venda de uma loja virtual que atua em todo o território nacional, vendendo produtos de diferentes departamentos. Além disso, a loja atua em diferentes canais de venda, como marketplace, loja própria, entre outros.

Premissas de negócio:
Ao analisar os dados, é importante ter em mente que existem algumas premissas de negócio que devem ser consideradas. A primeira elas é que, devido a um erro no sistema, algumas compras nao possuem informacoes de UF( Unidade Federativa). Para solucionar esse problema, foi decididoque essas compras serao consideradas como pertecentes ao estado de Mato Grosso do Sul (MS). A segunda premissa é que o preco final de um produto nao pode ser maior do que o preco com frete.

Métricas.
Com base nesse contexto e nas premissas de negócio estabelecidas, pdemos avaliar as seguintes métricas:

1. Departamentos mais vendidos: Analisando os dados de vendas, podemos identificar quais sao os departamentos mais populares entres os clientes. Essa informacao pode ser útil para entender quais sao os produtos mais procurados pelos clientes e ajustar a estratégia de venda da loja em conformidade.
2. Média de preco com frete por Nome de Departamento: Para enteder o comportamento de preco por departamento, podemos calcular a média de preco com frete por nome de departamento. Essa métrica pode ajudar a identificar quais sao os departamentos mais rentáveis e ajustar a precificacao de produtos de acordo com a margem desejada.
3. Quantidade de vendas por Mes: Analisando a quantidade de vendas realizadas em cada mes, podemos identificar sazonalidades no comportamento de compra dos clientes e planejar campanhas de marketing específicas para cada período.
4. Média de renda para cada tipo de canal de venda: Identificar a média de renda dos clientes em diferentes canais de venda pode ajudar a loja a adaptar a estratégia de marketing e vendas para cada público-alvo.
5. Média de idade de clientes por bandeira: Saber a faixa etária dos clientes por bandeira pode ajudar a identificar perfis de consumidores e ajustar a estraégia de venda para atender melhor cada público.
