
<h1 align="center">Business Case - Análise de Vendas</h1>

![new-used-gadget-exchange](https://github.com/user-attachments/assets/d1c3ffd8-3f63-46e8-b7fb-9de4a9ae0e97)


## Contexto
O setor comercial de uma rede de lojas fictícia de roupas deseja saber o resultado das vendas e desempenho de suas filiais ao longo do ano de 2024. Eles estabeleceram uma **meta mensal de R$7.000,00 de faturamento por loja** e desejam, através dessa análise, descobrir se a meta foi atingida ao longo do ano, bem como qual foi o desempenho geral da empresa, e quais lojas e produtos têm dado maior retorno nas vendas.

## Objetivos
Para responder aos pedidos da empresa, analisaremos o resultado das vendas de 2024 com base em 4 perguntas, descritas abaixo. Com isso, teremos o faturamento geral, por loja, produto e mês, o que vai nos apontar quais unidades, itens e período tiveram melhor desempenho naquele ano.

* Qual o faturamento de 2024?
* Que lojas mais venderam?
* Quais os produtos mais vendidos?
* Nossas lojas atingiram a meta mensal estabelecida?

## Estrutura do Projeto
### 1. Banco de dados
Abaixo o dicionário dos dados:

| Coluna | Descrição |
|----------|----------|
| Loja | Nome da filial  |
| Data   | Data da venda  |
| Produto  | Produto vendido  |
| Valor_Unitario | Valor de uma unidade do produto |
| Quantidade | Quantidade de produtos vendidos  |
| Valor_Total  | Valor total da venda (quantidade comprada * valor unitário) |

<br>

### 2. Respondendo às perguntas de negócio

**1. Qual o faturamento de 2024?**  
O faturamento total do ano foi de **R$461.743,30**. Analisando por unidade, Leblon e Ipanema contaram com os maiores faturamentos, respectivamente 28% e 21,8% do total.

| Loja | Faturamento | Porcentagem |
|:-----------:|:-------------------:|:-------------------:|
| 5  | 10% | R$6.263,18|
| 4  | 20% | R$5.742,40 |
| 3  | 40% | R$5.168,20 |
| 2  | 70% | R$4.485,60 |
| 1  | 90% | R$3.839,55 |  

**2. Que lojas mais venderam?**  
Contamos com um **total de 759 vendas, de 2.308 itens**. As unidades que mais venderam foram Leblon e Ipanema.

**3. Quais os produtos mais vendidos?**  
De maneira geral, **os itens tiveram distribuição semelhante em número de vendas e quantidade vendida**. A diferença se deu no faturamento, com** Camisa Linho, Oxford e Joa somando mais de 70% do faturamento total**. A tabela está ordenada pelo número de vendas.

| Produto | Nº de Vendas | Quantidade de Itens | Faturamento | % Faturamento |
|:-------:|:------------:|:-------------------:|:-----------:|:-------------:|
| Camisa Oxford | 158 | 480 | R$100.464,00 | 21,75% |
| Camiseta Navy | 157 | 479 | R$80.136,70 | 17,36% |
| Camiseta Joa | 151 | 480 | R$97.104,00 | 21,03% |
| Camiseta Pima | 149 | 423 | R$50.506,20 | 10,94% |
| Camisa Linho | 144 | 446 | R$133.532,40 | 28,92% |
| **Total** | **759** | **2.308** | **R$461.743,30** | **100%** |

**4. Nossas lojas atingiram a meta mensal estabelecida?**  
Aplicando o faturamento médio das lojas (faturamento total / 12 meses), apenas 3 das 5 lojas atingiram ou ultrapassaram a **meta estabelecida de R$7.000,00**, sendo elas **Leblon, Ipanema e Botafogo**. Todas as lojas contaram com oscilações, ou seja, ao longo do ano, houveram meses em que estavam acima ou abaixo da meta. Analisemos abaixo o desempenho de todas as lojas:

* **Loja do Leblon:** Faturamento médio de R$10.388,30. Com o melhor desempenho, ficou um pouco abaixo da meta apenas em setembro. Contou com picos no faturamento entre julho e agosto e tendência de crescimento a partir de outubro.

* **Loja de Ipanema:** Faturamento médio de R$8.370,72. Apresentou queda nas vendas no começo de 2024, passando a crescer entre março e abril. Após isso teve bom desempenho, estando acima ou muito próxima da meta no restante do ano.

* **Loja de Botafogo:** Faturamento médio de R$7.600,00. Ficou acima ou bem próximo da meta a maior parte do ano, estando muito abaixo apenas em julho.

* **Loja da Tijuca:** Faturamento médio de R$5.610,17. Com o pior desempenho, esteve acima ou próximo da meta apenas em 5 meses do ano. Começou e encerrou o ano com queda no faturamento.

* **Loja da Barra:** Faturamento médio de R$6.115,42. Ficou acima da meta apenas nos meses de julho, novembro e dezembro, contando com péssimo desempenho em setembro.

### 3. Como melhorar nossos resultados?
Há uma série de medidas que podemos adotar, conforme notas dos clientes nos diferentes fatores da análise (recência, frequência e valor), tais como:

* **Aumentar promoções nas lojas com menor faturamento:** Para as lojas com pior desempenho podemos aumentar as campanhas de promoções e descontos, a fim de incentivar o aumento das vendas nessas filiais. Ambas contaram com baixo faturamento no começo do ano (janeiro - abril), podemos voltar campanhas para datas comemorativas que ocorrem neste período. Devemos explorar também o que causou pico nas vendas nessas lojas e buscar fidelizar os clientes que compram nesse período, a fim de trazê-los também em outras épocas do ano.

* **Fidelizar clientes:** Para nossas lojas com melhor desempenho, podemos lançar programas de indicação, para obter mais clientes de perfil semelhante aos nossos de maior valor, assim como programas de fidelidade e premiações para esses clientes, aumentando seu engajamento com nossas lojas.

* **Focar em nossos produtos de maior faturamento:** Observamos que os produtos tiveram desempenho semelhante em número de vendas e quantidades vendidas, a diferença se deu no faturamento, devido, obviamente, ao preço dos produtos. Podemos realizar campanhas de marketing para estes produtos de maior valor, destacando suas qualidades e diferencial, e direcionando as campanhas para pessoas de perfil semelhante aos nossos clientes que adquirem essas camisas.
