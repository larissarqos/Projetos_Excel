<h1 align="center">📊 Análise RFV - Setor de Vendas</h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/6e8f0bb9-14e9-4fe7-a21d-5bc5b8616b20" alt="analise_vendas" width="1100" height="330"/>
</p>

## 📃 Contexto
Uma empresa fictícia busca entender melhor o comportamento de compra de seus clientes com o objetivo de otimizar estratégias de vendas e campanhas de marketing. Para isso, será realizada uma análise das vendas do último ano, considerando três fatores principais: valor gasto, frequência de compra e tempo desde a última compra.

***

## 🛠️ Ferramentas e Métodos Utilizados
* Microsoft Excel (fórmulas, tabelas dinâmicas, gráficos, slicers)
* Limpeza e tramento dos dados
* Engenharia de atributos
* Business Intelligence

***

## 🎯 Objetivos
Aplicaremos a análise RFV (Recência, Frequência e Valor), atribuindo notas de 1 (pior) a 5 (melhor) em cada fator, para responder às seguintes perguntas:

* Qual a recência dos clientes?
* Qual a frequência de compras?
* Qual o valor médio gasto?
* Qual o RFV geral da base de clientes?

Os resultados obtidos após a análise nos farão entender o comportamento de nossos clientes e obter insights sobre que decisões tomar de acordo com o seu perfil.

***

## 📐 Métricas utilizadas
Métricas utilizadas ao estabelecer a recência, frequência e valor.

#### 🔸 Recência
Reflete o tempo desde a última compra. Quanto mais recente, maior a nota.
  
| Recência    | Até (dias) |
|:-----------:|:----------:|
| 5  | 30  |
| 4  | 60  |
| 3  | 120 |
| 2  | 180 |
| 1  | 365 |  

<br>

#### 🔸 Frequência
Número de compras realizadas no período. Quanto mais frequente, maior a nota. Os valores atribuídos para cada nota levaram em consideração a frequência de compra dos clientes na base de dados.
  
| Frequência  | Ao menos (quantidade de pedidos) |
|:-----------:|:--------------------------------:|
| 5  | 12 |
| 4  | 11 |
| 3  | 8  |
| 2  | 5  |
| 1  | 1  |  

<br>

#### 🔸 Valor
Representa o ticket médio do cliente. A nota é atribuída com base em percentis.
| Valor   | Percentil | Ticket Médio (aproximado) |
|:-------:|:---------:|:-------------------------:|
| 5  | 10% | ≥ R$6.263,18 |
| 4  | 20% | ≥ R$5.742,40 |
| 3  | 40% | ≥ R$5.168,20 |
| 2  | 70% | ≥ R$4.485,60 |
| 1  | 90% | ≥ R$3.839,55 | 

***

## 🧱 Estrutura do Projeto

### 1. Banco de dados

| Coluna | Descrição |
|--------|-----------|
| Cliente       | Código do cliente                                                  |
| Recencia_Dias | Dias desde a última compra                                         |
| Ticket_Medio  | Valor médio gasto por pedido (total gasto / quantidade de pedidos) |
| Pedidos       | Quantidade total de pedidos do cliente                             |
| Recencia      | Nota de recência atribuída (1 a 5)                                 |
| Frequencia    | Nota de frequência atribuída (1 a 5)                               |
| Valor         | Nota de valor atribuída (1 a 5)                                    |
| RFV           | Soma das três notas anteriores (máximo de 15)                      |

***

### 📍 2. Respondendo às perguntas de negócio

#### 📌 1. Qual a recência?
A maioria dos clientes obteve **nota 5 em recência**, ou seja, realizaram uma compra nos últimos 30 dias. Esse é um forte indicativo de **engajamento recente com a empresa**. Abaixo distribuição das notas:
| Nota  | Distribuição | % do Total |
|:-----:|:------------:|-----------:|
| 5  | 626 | 63,6% |
| 4  | 209 | 20,9% |
| 3  |  93 |  9,3% |
| 2  |  18 |  1,8% |
| 1  |  54 |  5,4% | 

<br>

#### 📌 2. Qual a frequência?
A distribuição foi concentrada entre as **notas 5 e 4**, revelando um bom volume de clientes que **compram com regularidade**. Abaixo distribuição das notas:
| Nota  | Distribuição | % do Total |
|:-----:|:------------:|-----------:|
| 5  | 300 | 30%   |
| 4  | 376 | 37,6% |
| 3  | 247 | 24,7% |
| 2  |  76 |  7,6% |
| 1  |   1 |  0,1%   | 

<br>

#### 📌 3. Qual o valor?
O ticket médio dos clientes ficou concentrado entre as **notas 3 e 4, com uma boa proporção também na nota 5**. Isso indica um perfil de **gasto moderado, com margem para crescimento**. Abaixo distribuição das notas:
| Nota  | Distribuição | % do Total |
|:-----:|:------------:|-----------:|
| 5  | 199 | 19,9% |
| 4  | 202 | 20,2% |
| 3  | 299 | 29,9% |
| 2  | 200 | 20%   |
| 1  | 100 | 10%   | 

<br>

#### 📌 4. Qual o RFV geral da empresa?  
A pontuação mais comum foi **entre 12 e 13** (máximo = 15), o que mostra que **muitos clientes são recentes**, **compram com frequência** e têm **valor médio de compra razoável**. Podemos considerar esses perfil como muito valioso para a empresa, com **alto potencial de fidelização**. Abaixo distribuição das notas:

| Nota  | Distribuição | % do Total |
|:-----:|:------------:|-----------:|
| 15 |  37 |  3,7% |
| 14 | 101 | 10,1% |
| 13 | 181 | 18,1% |
| 12 | 220 | 22%   |
| 11 | 175 | 17,5% |
| 10 | 130 | 13%   |
|  9 |  71 |  7,1% |
|  8 |  42 |  4,2% |
|  7 |  21 |  2,1% |
|  6 |  15 |  1,5% | 
|  5 |   6 |  0,6% |
|  4 |   1 |  0,1% |

***

### 3. 📈 Recomendações Estratégicas
Com base nas pontuações obtidas, é possível definir estratégias direcionadas para os diferentes perfis de clientes:

**🟧 Baixa recência:** Cliente hibernando ou quase perdido, estão inativos há muito tempo.  

**🟩 Ações:** Reativação com campanhas sazonais, e-mails personalizados e promoções exclusivas.

--

**🟧 Baixa frequência:** Contamos com alta recência, a baixa frequência pode indicar pouca regularidade nas compras.  

**🟩 Ações:** Nutrir o relacionamento com ofertas de produtos complementares, campanhas de pontos que geram desconto com prazo de validade, buscando manter a frequência de compras desses clientes.

--

**🟧 Baixo valor:** Percebemos, em nossa análise, baixo valor (muitas notas entre 3 e 4) mesmo com alta frequência e recência.  

**🟩 Ações:** Incentivar compras de maior valor com combos, frete grátis acima de certo valor ou upselling, a fim de aumentar o ticket médio desse perfil.

--
**🟧 Alto RFV:** Clientes que são frequentes, recentes e têm alto valor. Atualmente representam 3,7% (Nota de RFV geral = 15) dos clientes da empresa.  
**🟩 Ações:** Manter e recompensar — programas de fidelidade, vantagens VIP, campanhas de indicação, recompensas (como condições especiais de pagamento, descontos, brindes), premiações.

***

*Este projeto foi desenvolvido como parte do meu portfólio em análise de dados. Sinta-se à vontade para explorar os dados, sugerir melhorias ou entrar em contato!*
