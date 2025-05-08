<h1 align="center">📊 Análise RFV - Setor de Vendas</h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6e8f0bb9-14e9-4fe7-a21d-5bc5b8616b20" alt="analise_vendas" width="1100" height="330"/>
</p>

## Contexto
Uma empresa fictícia busca entender melhor o comportamento de compra de seus clientes para melhorar suas vendas e estratégia das campanhas de marketing. Para isso, desejam analisar o último ano de vendas, considerando o valor gasto por seus clientes e a frequência de compras.

## Objetivos
Para atender à demanda da empresa, aplicaremos a análise de RFV (Recência, Frequência e Valor), aplicando 1 como pior nota e 5 para melhor nota em cada um dos fatores da análise.

* Qual a recência?
* Qual a  frequência?
* Qual o valor? 
* Qual o RFV geral da empresa?

## Estrutura do Projeto
### 1. Banco de dados
Abaixo o dicionário dos dados:

| Coluna | Descrição |
|----------|----------|
| Cliente | Código do cliente  |
| Recencia_Dias   | Dias desde a última compra   |
| Ticket_Medio   | Valor médio gasto pelo cliente (total gasto / quantidade de pedidos)  |
| Pedidos | Quantidade de Pedidos|
| Recencia  | Cálculo de recência (o quão recente foi a última compra)  |
| Frequencia  | Cálculo de frequência (o quão frequente o cliente compra)  |
| Valor  | Cálculo de valor (quão alto é o valor de compra do cliente)  |
| RFV | Cálculo geral considerando a recência, frequência e valor  |


<br>

### Métricas utilizadas
Métricas utilizadas ao estabelecer a recência, frequência e valor.
* **Cálculo de recência:** Notas de 1 a 5, sendo 5 a compra mais recente (até 30 dias) e 1 a compra menos recente (até 365 dias).
  
| Recência    | Até dias |
|:-----------:|:-------------------:|
| 5  | 30 |
| 4  | 60 |
| 3  | 120|
| 2  | 180 |
| 1  | 365 |  


* **Cálculo de frequência:** Utilizamos notas de 1 a 5, sendo 5 para a maior frequência (12 compras) e 1 para a menor frequência (1 compra). Os valores atribuídos para cada nota levaram em consideração a frequência de compra dos clientes.
  
| Frequência    | Ao menos |
|:-----------:|:-------------------:|
| 5  | 12 |
| 4  | 11 |
| 3  | 8 |
| 2  | 5 |
| 1  | 1 |  


* **Cálculo de valor:** Utilizamos notas de 1 a 5, sendo 5 para o maior valor de compra e 1 para o menor. Os valores aplicados para cada nota levaram em consideração o ticket médio dos clientes. O valor de ticket médio 10% mais alto levou nota 5,  20% mais alto nota 4, e segue de acordo com a tabela.

| Valor   | % | Ticket Médio |
|:-----------:|:-------------------:|:-------------------:|
| 5  | 10% | R$6.263,18|
| 4  | 20% | R$5.742,40 |
| 3  | 40% | R$5.168,20 |
| 2  | 70% | R$4.485,60 |
| 1  | 90% | R$3.839,55 |  


<br>

### 2. Respondendo às perguntas de negócio

**1.Qual a recência?**  
A recência indica o tempo desde a última compra, através dela podemos mensurar o engajamento de nossos clientes com a empresa. A nota de recência da empresa é **majoritariamente 5**, isso significa que muitos clientes realizaram compras nos últimos 30 dias.

**2. Qual a frequência?**  
A frequência indica o quão frequente o cliente tem comprado com a empresa. Com essa informação podemos mensurar o engajamento de nossos clientes. Para a frequência, contamos com uma **maior distribuição entre as notas 5 e 4**, o que também é um bom indicativo.

**3. Qual o valor?**  
O valor indica qual o montante gasto pelos clientes com nossos produtos e, através disso, descobrimos quais os clientes de maior valor para a empresa. Contamos com uma **maior quantidade de notas 3 e então 4 e 5**.

**4. Qual o RFV geral da empresa?**  
Analisando o total de notas, o comportamento de compra dos nossos clientes possui a **maior parte das notas entre 12 e 13**, o que é um bom indicativo, considerando a nota máxima como 15. Voltando para as perguntas anteriores, sabemos que a maior parte deles têm **5 em recência, 5 ou 4 em frequência e 3 em valor**, o que justifica essa maior concentração nos valores 12 e 13 no gráfico abaixo.

<br>

### 3. Como prosseguir com meus clientes, de acordo com a análise RFV?
Há uma série de medidas que podemos adotar, conforme notas dos clientes nos diferentes fatores da análise (recência, frequência e valor), tais como:

* **Baixa recência:** É um cliente hibernando ou quase perdido, pois uma baixa recência indica muito tempo desde a última compra. É importante trazê-lo de volta através de promoções, ofertas relâmpago ou campanhas de reativação.

* **Baixa frequência:** Clientes com pouca frequência, mas alta ou média recência, pode indicar que são novos. São clientes promissores, é importante construir um relacionamento com eles, aplicando ofertas e descontos especiais.

* **Baixo valor:** Na nossa análise, percebemos muitos clientes com notas em valor entre 3 e 4, mesmo contando com alta frequência e recência. Isso pode ocorrer se os produtos adquiridos têm menor preço, por exemplo. É importante incentivar esses clientes com promoções especiais, buscando aumentar seu ticket médio.

* **Alto RFV:** Clientes com alta recência, frequência e valor são fiéis e é importante mantê-los. Uma boa forma de fazer isso é aplicando programas de fidelidade, recompensas/pontos e mesmo premiações para estes, o que vai fortalecer seu laço e fidelidade com a empresa. Um programa de recomendação também pode funcionar muito bem, pois estaremos influenciando nossos melhores clientes a indicar nossos produtos/serviços a pessoas com perfil próximo ao deles, o que pode gerar mais clientes promissores.

