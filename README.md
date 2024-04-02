# Dashboard Análise de Perfil
![Dashboard de Verdas](https://github.com/waltercrastobr/Dashboard-Analise-Perfil/blob/main/dashboard_analise_perfil.PNG)

## Apresentação do Projeto:

Este projeto consiste na análise de um banco de dados relacionado ao perfil dos clientes de um site de venda de automóveis. A [base de dados](https://github.com/waltercrastobr/Dashboard-Analise-Perfil/blob/main/banco_de_dados.sql) contém informações sobre os clientes, como gênero, estado civil, faixa etária, faixa salarial, entre outros. O objetivo é criar um dashboard para visualização de dados e gerar insights que possam ser utilizados para otimizar as estratégias de vendas e marketing das lojas de automóveis.

## Relatório sobre as Queries e Insights feitos a partir do [Dashboard de Análise de Perfil](https://github.com/waltercrastobr/Dashboard-Analise-Perfil/blob/main/Projeto%20An%C3%A1lise%20de%20Perfil.xlsx):

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


Com base na análise do Dashboard de vendas criado a partir dos códigos em SQL, foram identificados os seguintes insights e decisões para melhoria de vendas:

Perfil dos Clientes:

Gênero: Cerca de 60% dos compradores/visitantes são mulheres, sugerindo a importância de estratégias de marketing direcionadas a esse público.

Status Profissional: O status profissional mais frequente é o de CLT, com 65% dos clientes. Isso indica que a maioria dos clientes possui uma fonte de renda estável.Veículos Mais Vendidos:

Classificação: 96% dos veículos mais vendidos são seminovos, com mais de 2 anos de uso. Isso sugere que os clientes têm preferência por veículos que oferecem um bom custo-benefício.

Faixa Salarial e Idade dos Veículos: Faixa Salarial: A faixa salarial onde se concentram os compradores é de 5 mil a 10 mil reais. Isso indica a necessidade de oferecer opções de financiamento e promoções que se adequem a esse perfil de cliente.

Idade dos Veículos: Cerca de 70% dos veículos comprados possuem 6 anos ou mais. Isso sugere que os clientes estão interessados em veículos mais antigos, o que pode indicar a necessidade de ampliar o estoque de veículos nessas condições.

Marcas e Modelos Populares: Popularidade das Marcas: As marcas mais populares vendem mais. Dentro dessas marcas, são vendidos os carros de custo mais baixo. Isso sugere que os clientes estão buscando por marcas confiáveis com preços acessíveis.

Com base nesses insights, as seguintes decisões de melhoria de vendas podem ser tomadas:

Estratégias de Marketing: Desenvolver campanhas de marketing direcionadas ao público feminino, destacando modelos de veículos que atendam às suas preferências.Promoções e Financiamento: Oferecer promoções e condições de financiamento especiais para clientes CLT e na faixa salarial de 5 mil a 10 mil reais, incentivando a compra de veículos seminovos.

Diversificação do Estoque: Ampliar o estoque de veículos seminovos e com mais de 6 anos de uso, para atender à demanda dos clientes por veículos nessas condições.

Diferenciação de Produtos: Oferecer modelos de veículos populares com preços competitivos, dentro das marcas mais vendidas, para atrair clientes em busca de custo-benefício.

Essas decisões visam aumentar a atratividade da oferta da empresa, atendendo às necessidades e preferências dos clientes identificados na análise do Dashboard de vendas.
