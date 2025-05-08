<h1 align="center">Análise de Vendas - Serviços de Assinatura</h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0a2cf568-61c5-4222-8bc8-d7ed9b11ad61" alt="analise_vendas" width="500" height="350"/>
</p>

## 📃 Contexto
A área comercial de uma empresa fictícia de serviços de assinatura deseja compreender seu desempenho no mês. Os objetivos incluem entender os principais fatores que impactam o faturamento e a percepção dos clientes sobre produtos e atendimento, a fim de orientar melhorias estratégicas no setor comercial.

***

## 🛠️ Ferramentas e Métodos Utilizados
- Microsoft Excel (fórmulas, tabelas dinâmicas, gráficos)
- ETL
- Análise dos dados
- Businnes Intelligence

***

## 🎯 Objetivos
A análise busca, além de diagnosticar o desempenho mensal da empresa, identificar oportunidades para aumentar o faturamento e a satisfação dos clientes. As perguntas que guiarão nossa análise são:

- Qual foi o faturamento do mês?
- Que serviço é o mais adquirido?
- Qual é o perfil dos clientes?
- Qual a avaliação dos serviços?
  
***

## 🧱 Estrutura do Projeto
### 1. Banco de Dados

| Coluna           | Descrição |
|------------------|-----------|
| CPF              | CPF do cliente                                                |
| Nome             | Nome completo                                                 |
| Genero           | Gênero (masculino ou feminino)                                |
| Nivel_Estudos    | Formação (médio, superior, pós-graduação, mestrado, doutorado)|
| Interesse/Hobby  | Interesses/Hobbies                                            |
| Regiao           | Estado de residência                                          |
| Data_Nasc        | Data de nascimento                                            |
| Idade            | Idade                                                         |
| Faixa_Etaria     | Faixa etária                                                  |
| Avaliacao        | Avaliação dada ao serviço                                     |
| Assinatura       | Tipo de serviço contratado                                    |
| Mensalidade      | Valor mensal do serviço                                       |

***

### 📍 2. Respondendo às perguntas de negócio

** 📌 1. Qual foi o faturamento do mês?**  
O faturamento foi de **R$26.467,80**. Mantido esse ritmo, o ano pode fechar com aproximadamente **R$300.000**.

<br>
  
** 📌 2. Que serviço é o mais adquirido?**  
O produto que conta com mais assinantes é o **Magic Box, 35% do total de assinaturas**. Consideremos o total de assinaturas por serviço e seus respectivos impactos no faturamento:

| Serviço     | Valor (R$)          | Total Assinaturas     | Faturamento     |
|:-----------:|:-------------------:|:---------------------:|:---------------:|
| Deluxe Box  | R$35,90             | 168                   | R$6.031,20      |
| Magic Box   | R$9,90              | 266                   | R$2.633,40      |
| Premium X   | R$79,90             | 136                   | R$10.866,40     |
| Safe Watch  | R$29,90             | 232                   | R$6.936,80      |
| **Total**   | --                  | **802**               | **R$26.467,80** |

*Insight: Serviços de menor valor concentram a maior parte das assinaturas, mas têm menor peso no faturamento. Notamos que, apesar de contar com o maior número de assinaturas, Magic Box é o produto com menor impacto no faturamento.*

<br>

** 📌 3. Qual o perfil dos clientes?**  
Atualmente, contamos com **802 assinantes**. Considerando o estado em que moram, a maior parte deles é do **Rio Grande do Sul (51%)**, seguido do **Paraná (27%)** e **Santa Catarina (22%)**. De acordo com o gênero e faixa etária, a maior parte dos nosso clientes é do **sexo masculino**. A faixa etária predominante é de **35-44 e 54-70, para ambos os sexos**.

*Total de assinantes:* 802

*Distribuição geográfica:*
- Rio Grande do Sul – 51%
- Paraná – 27%
- Santa Catarina – 22%

*Gênero predominante:* Masculino

*Faixas etárias predominante:* 35–44 e 54–70 (ambos os sexos)

<br>

** 📌 4. Qual a avaliação dos nossos serviços?**  
De maneira geral, nossos serviços têm boas avaliações a respeito do produto e atendimento. As principais reclamações são sobre a falta de itens e atraso na entrega.

***

### 3. 📈 Como melhorar nosso faturamento e atendimento?
De acordo com a análise dos dados, segue sugestões de ações para melhorias:

**Relativas ao faturamento**

* **Oferecer upgrades das assinaturas:** Podemos incentivar nossos clientes a adquirirem nossos serviços de maior preço, através de campanhas focadas no diferencial que esses produtos têm a oferecer.  Um maior número de assinaturas do Premium X, por exemplo, geraria um aumento significativo em nosso faturamento.

* **Aumentar a quantidade de clientes no Paraná e Santa Catarina:** O Rio Grande do Sul detém mais da metade de nossas assinaturas, pensemos em como expandir nossos serviços também nos outros estados. Podemos incluir campanhas de marketing para aumentar as vendas nesses estados, descontos para clientes que indicarem o serviço e mesmo promoções voltadas para leads dessa região.

* **Investir nos perfis que mais contrataram nossos serviços:** A maioria de nossos assinantes possui faixa etária entre 35-44 e 54-70. O impacto de gênero em nosso faturamento não é tão significativo, o que significa que podemos voltar nossas campanhas para ambos os sexos. Começar pedindo feedback desse perfil de clientes sobre nossos produtos (porque adquiriram/recomendariam) será um bom norte para basear nossas campanhas de marketing.

**Relativas ao atendimento**
* **Melhorar a qualidade das nossas entregas:** A maior parte das reclamações de nossos clientes têm relação com a entrega (faltando item, atraso na entrega, embalagem danificada, produto com defeito). Devemos direcionar essas reclamações ao setor responsável pelo embalamento e despacho dos produtos e certificar-se de que está sendo feito corretamente, de que há teste do produto antes do envio e verificação de que todos os itens estão na embalagem. Para além disso, avaliar junto à transportadora quais as causas de atraso na entrega e o que pode ser feito a respeito disso.

* **Analisar a qualidade do suporte ao cliente:** É preciso avaliar a qualidade do nosso suporte, se os canais têm bom atendimento, se é atencioso com nossos clientes. Quanto tempo até a solução das queixas? As soluções oferecidas levam à satisfação dos clientes? Propor desconto nas mensalidades em caso de erros da empresa e agilizar a troca de produtos com defeito pode amenizar as reclamações relacionadas ao atendimento. 

