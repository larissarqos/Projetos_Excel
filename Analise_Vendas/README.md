
<h1 align="center"> Análise de Vendas </h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/779ac29a-fc13-4357-8dca-14d2e2abb3c7" alt="analise_vendas" width="500"/>
</p>

## 📃 Contexto  
O setor comercial de uma rede fictícia de lojas de roupas deseja avaliar o desempenho de suas filiais ao longo do ano de 2024. Com uma **meta mensal de R$7.000,00 por loja**, a empresa busca entender se os objetivos foram alcançados, identificar quais unidades e produtos geraram maior retorno, além de obter uma visão consolidada sobre seu faturamento anual.

***

## 🛠️ Ferramentas e Métodos Utilizados
- Microsoft Excel (fórmulas, tabelas dinâmicas, gráficos)
- ETL
- Análise dos dados
- Businnes Intelligence
  
***

## 🎯 Objetivos  
Para atender à demanda da empresa, realizamos uma análise exploratória das vendas de 2024, com foco nas seguintes questões-chave:

- Qual foi o faturamento de 2024?   
- Quais lojas mais se destacaram em vendas?  
- Quais foram os produtos mais vendidos?  
- As lojas atingiram a meta mensal estabelecida?

Com base nessas perguntas, conseguimos avaliar o desempenho por loja, produto e mês — oferecendo à empresa uma visão clara sobre os pontos fortes e oportunidades de melhoria.

***

## 🧱 Estrutura do Projeto  

### 1. Banco de dados  

| Coluna           | Descrição                                              |
|------------------|--------------------------------------------------------|
| Loja             | Nome da filial                                         |
| Data             | Data da venda                                          |
| Produto          | Produto vendido                                        |
| Valor_Unitario   | Valor unitário do produto                              |
| Quantidade       | Quantidade vendida                                     |
| Valor_Total      | Valor total da venda (Quantidade × Valor Unitário)     |

***

### 2. 📍 Respondendo às perguntas de negócio

#### 📌 1. Qual foi o faturamento de 2024?  
O faturamento total do ano foi de **R$461.743,30**. As lojas do **Leblon** e de **Ipanema** lideraram as vendas, responsáveis por **28%** e **21,8%** do total, respectivamente.

| Loja     | Faturamento     | Participação no total |
|----------|------------------|------------------------|
| Leblon   | R$129.020,00     | 28%                    |
| Ipanema  | R$100.448,64     | 21,8%                  |
| Botafogo | R$91.200,00      | 19,8%                  |
| Barra    | R$73.385,08      | 15,9%                  |
| Tijuca   | R$67.689,58      | 14,6%                  |
| **Total**| **R$461.743,30** | **100%**               |

<br>

#### 📌 2. Quais lojas mais venderam?  
Em 2024, foram registradas **759 vendas**, totalizando **2.308 itens**. As filiais do **Leblon** e de **Ipanema** lideraram tanto em número de vendas quanto em faturamento.

<br>

#### 📌 3. Quais os produtos mais vendidos?  
As vendas foram bem distribuídas entre os produtos. Porém, em termos de faturamento, os destaques foram **Camisa Linho**, **Oxford** e **Joa**, que juntas representaram mais de **70% do faturamento**.

| Produto         | Nº de Vendas | Quantidade | Faturamento      | % do Total     |
|------------------|--------------|------------|------------------|----------------|
| Camisa Oxford    | 158          | 480        | R$100.464,00     | 21,75%         |
| Camiseta Navy    | 157          | 479        | R$80.136,70      | 17,36%         |
| Camiseta Joa     | 151          | 480        | R$97.104,00      | 21,03%         |
| Camiseta Pima    | 149          | 423        | R$50.506,20      | 10,94%         |
| Camisa Linho     | 144          | 446        | R$133.532,40     | 28,92%         |
| **Total**        | **759**      | **2.308**  | **R$461.743,30** | **100%**       |

<br>

#### 📌 4. As lojas atingiram a meta mensal de R$7.000,00? **  
Com base no faturamento médio mensal por loja (faturamento total ÷ 12), apenas **3 das 5 filiais** alcançaram ou superaram a meta: **Leblon, Ipanema e Botafogo**.

**Resumo por loja:**

- **Leblon** – R$10.388,30/mês: Melhor desempenho do ano. Abaixo da meta apenas em setembro, com crescimento contínuo a partir de outubro.

- **Ipanema** – R$8.370,72/mês: Crescimento a partir de março. Consistente no restante do ano, sempre próxima ou acima da meta.

- **Botafogo** – R$7.600,00/mês: Regular ao longo do ano, exceto em julho.

- **Barra** – R$6.115,42/mês: Acima da meta apenas em julho, novembro e dezembro. Desempenho fraco em setembro.

- **Tijuca** – R$5.610,17/mês: Atingiu ou superou a meta em apenas 5 meses. Início e fim do ano com queda nas vendas.

***

### 3. 📈 Como melhorar os resultados?
Com base na análise dos dados e padrões identificados, algumas ações estratégicas podem ser adotadas:

#### 🟩 Ações por loja
- **Campanhas promocionais focadas nas lojas com menor desempenho**  
  Promoções sazonais, descontos progressivos e ações em datas comemorativas podem ajudar a impulsionar vendas, principalmente no primeiro trimestre.
  
#### 🟦 Ações por produto
- **Aproveitar o potencial dos produtos mais lucrativos**  
  Campanhas de marketing direcionadas para os best-sellers (como Camisa Linho e Oxford) podem alavancar ainda mais o faturamento.

### 🟪 Ações por perfil de cliente**
- **Fidelizar clientes**
  Entender os picos de vendas e oferecer benefícios para clientes recorrentes pode aumentar a retenção.
  Lançar programas de fidelização e indicação, a fim manter nossos cliente fiéis e obter clientes de perfil semelhante a estes.

#### 🟧 Acompanhamento contínuo
- **Monitoramento mensal por loja e produto**  
  Relatórios visuais e metas ajustadas com base no desempenho sazonal ajudam na tomada de decisão mais rápida e eficiente.
  
---

*Este projeto foi desenvolvido como parte do meu portfólio em análise de dados. Sinta-se à vontade para explorar os dados, sugerir melhorias ou entrar em contato!*
