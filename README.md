# Dashboard Análise de Perfil
![Dashboard de Verdas](https://github.com/waltercrastobr/Dashboard-Analise-Perfil/blob/main/dashboard_analise_perfil.PNG)

## Apresentação do Projeto:

Este projeto consiste na análise de um banco de dados relacionado ao perfil dos clientes de um site de venda de automóveis. A base de dados contém informações sobre os clientes, como gênero, estado civil, faixa etária, faixa salarial, entre outros. O objetivo é criar um dashboard para visualização de dados e gerar insights que possam ser utilizados para otimizar as estratégias de vendas e marketing das lojas de automóveis.

## Relatório sobre as Queries e Insights feitos a partir do Dashboard de Análise de Perfil dos clientes:

### Query 1 (Gênero dos leads):

- Utilizo a tabela sales.customers para obter informações sobre os clientes.
- Uso uma tabela auxiliar temp_tables.ibge_genders com informações de gênero dos clientes para fazer o match.
- Calculo a quantidade de leads por gênero.
- Apresento o número de leads por gênero.

### Query 2 (Status profissional dos leads):

- Utilizo a tabela sales.customers para obter informações sobre os clientes.
- Calculo a proporção de leads por status profissional.
- Apresento a distribuição percentual dos leads por status profissional.

### Query 3 (Faixa etária dos leads):

- Utilizo a tabela sales.customers para obter informações sobre os clientes.
- Calculo a proporção de leads por faixa etária.
- Apresento a distribuição percentual dos leads por faixa etária.

### Query 4 (Faixa salarial dos leads):

- Utilizo a tabela sales.customers para obter informações sobre os clientes.
- Calculo a proporção de leads por faixa salarial.
- Apresento a distribuição percentual dos leads por faixa salarial.

### Query 5 (Classificação dos veículos visitados):

- Utilizo a tabela sales.funnel para obter informações sobre as visitas ao site.
- Utilizo a tabela sales.products para obter informações sobre os veículos.
- Calculo a quantidade de veículos visitados classificados como novos ou seminovos.
- Defino a classificação com base no ano de fabricação dos veículos.
- Apresento a quantidade de veículos visitados por classificação.

### Query 6 (Idade dos veículos visitados):

- Utilizo a tabela sales.funnel para obter informações sobre as visitas ao site.
- Utilizo a tabela sales.products para obter informações sobre os veículos.
- Calculo a proporção de veículos visitados por idade.
- Defino as faixas de idade dos veículos com base no ano de fabricação.
- Apresento a distribuição percentual de veículos visitados por idade.

### Query 7 (Veículos mais visitados por marca):

- Utilizo a tabela sales.funnel para obter informações sobre as visitas ao site.
- Utilizo a tabela sales.products para obter informações sobre os veículos.
- Calculo a quantidade de visitas por modelo de veículo e marca.
- Apresento os modelos de veículos mais visitados por marca.

## Relatório de Insights:

É importante destacar que, para alguns gráficos, foram utilizados apenas os dados mais recentes do banco de dados (agosto de 2021) para condensar a análise, uma vez que o padrão de informação se repete proporcionalmente nos outros meses.

Após analisar os dados das vendas de produtos, podemos extrair insights valiosos que podem orientar estratégias futuras. Abaixo estão as principais conclusões:

- Ticket Médio e Receita Total: O ticket médio não apresenta uma grande variação ao longo do tempo, indicando estabilidade nos preços dos produtos. No entanto, a receita total aumenta consideravelmente entre os meses de abril e julho de 2021, mostrando que o aumento das vendas não está diretamente ligado ao ticket médio.

- Leads e Taxa de Conversão: O número de leads influencia diretamente na taxa de conversão em compras e, consequentemente, no aumento da receita total. Isso significa que quanto mais a página é acessada, maiores são as chances de compra, destacando a importância de investir em estratégias para atrair mais leads.

- Região de Maior Concentração de Compras: As análises indicam uma concentração de compras na região mais ao sul do país, com destaque para São Paulo e a região sul. Isso sugere que investir em marketing e campanhas específicas para essas regiões pode gerar um retorno significativo.

- Marcas Mais Populares: As marcas Fiat, Chevrolet e Volkswagen apresentam uma quantidade considerável de compras em comparação com outras marcas. Investir em promoções e estratégias de marketing para essas marcas pode atrair mais clientes e aumentar as vendas.

- Padrões de Visita ao Site: O número de visitas ao site diminui ao longo dos dias úteis na semana, com pico na segunda-feira e queda gradual até o domingo. Isso sugere que estratégias de promoção e divulgação de produtos devem ser mais intensas no início da semana, quando o tráfego no site é maior.

### Estratégias importantes a partir dessa Análise:

- Investimento no Site: Melhorar a experiência do usuário no site, tornando-o mais rápido, responsivo e fácil de navegar, pode aumentar a taxa de conversão. Além disso, investir em otimização de mecanismos de busca (SEO) e em estratégias de marketing digital, como anúncios pagos e marketing de conteúdo, pode atrair mais visitantes qualificados para o site.

- Marketing para Marcas Populares: Criar campanhas de marketing específicas para as marcas Fiat, Chevrolet e Volkswagen, destacando seus produtos e ofertas exclusivas, pode atrair mais clientes interessados nessas marcas e aumentar as vendas.

- Foco em Regiões Estratégicas: Concentrar esforços de marketing e vendas em regiões como São Paulo, Minas Gerais e região sul, onde há uma maior concentração de compras, pode gerar um retorno mais rápido e eficaz sobre o investimento.

- Promoções Estratégicas: Realizar promoções e ofertas especiais no início da semana, quando o tráfego no site é maior, pode aumentar as vendas e a receita. Essas promoções podem incluir descontos, brindes ou condições especiais de pagamento.

- Personalização e Segmentação: Utilizar técnicas de personalização e segmentação de clientes para oferecer produtos e ofertas mais relevantes para cada perfil de cliente pode aumentar a taxa de conversão e a fidelização do cliente.

- Acompanhamento e Análise Contínua: Monitorar constantemente os resultados das estratégias implementadas e realizar análises regulares dos dados pode ajudar a identificar novas oportunidades de melhoria e ajustar as estratégias conforme necessário.

Essas estratégias podem ajudar a impulsionar as vendas e a receita, aproveitando os insights obtidos a partir da análise dos dados das vendas de produtos.

Por fim, o Dashboard de Vendas revelou insights essenciais para impulsionar o desempenho das vendas de produtos. Ficou claro que o foco em atrair mais leads e aprimorar a experiência do usuário no site são estratégias-chave para aumentar a taxa de conversão e, consequentemente, a receita. Além disso, a concentração de compras em regiões específicas e em marcas populares indica a necessidade de direcionar esforços de marketing e vendas para esses segmentos. A análise dos padrões de visitas ao site também destacou a importância de realizar promoções estratégicas no momento certo para aproveitar o aumento no tráfego. Essas recomendações, aliadas a uma análise contínua dos dados, têm o potencial de impulsionar significativamente o crescimento e o sucesso do negócio.
