# Análise de Turnover em Recursos Humanos

## 1. Visão Geral do Projeto
Este projeto tem como objetivo principal investigar as causas da alta taxa de turnover em uma empresa fictícia, com foco particular nos departamentos de **Vendas** e **Recursos Humanos (RH)**.  
Utilizando técnicas de **análise descritiva** e **exploratória de dados**, buscamos identificar padrões, testar hipóteses e extrair insights valiosos para propor recomendações estratégicas ao departamento de RH.

---

## 2. Fonte de Dados
Os dados utilizados para esta análise foram obtidos de um dataset público e fictício de uma empresa de RH.  

**Fonte:** *HR Analytics Dataset*

---

## 3. Metodologia de Análise
A análise seguiu um processo estruturado, utilizando as seguintes etapas e técnicas:

- **Análise Descritiva:**  
  Cálculo de médias e distribuições para resumir as principais características dos dados, como satisfação no trabalho, renda mensal e tempo na empresa.

- **Análise Exploratória de Dados (AED):**  
  Criação de visualizações (*gráficos de barras, de caixa e de dispersão*) para identificar e comunicar padrões de forma visualmente intuitiva.

- **Limpeza e Transformação de Dados:**  
  A coluna `Attrition` foi renomeada para valores mais claros (*Saiu* e *Ficou*) para facilitar a leitura.

- **Análise Comparativa:**  
  Comparação entre os funcionários que saíram da empresa e os que permaneceram, com foco nos departamentos de **Vendas** e **RH**.

---

## 4. Principais Descobertas e Insights
A análise de dados revelou insights que desafiaram as suposições iniciais:

- **Turnover por Idade (Vendas):**  
  A maior taxa de turnover foi encontrada na faixa etária mais jovem (18-25 anos), com uma taxa de **43,90%** no departamento de Vendas.

- **Turnover por Gênero (Vendas):**  
  A alta rotatividade na faixa etária mais jovem é ainda mais acentuada entre o público **feminino**.

- **Disparidade Salarial (Vendas):**  
  O gráfico de caixa mostrou uma diferença na distribuição de renda mensal entre os gêneros no departamento de Vendas, sugerindo uma possível **disparidade salarial**, que pode ser um fator de insatisfação.

- **Análise de Cargos (RH):**  
  Nenhum gerente deixou a empresa, indicando que o turnover está concentrado em outros cargos (*Human Resources*).

---

## 5. Recomendações Estratégicas
Com base nos resultados, as seguintes recomendações foram elaboradas para o time de RH:

- **Foco em Retenção da Geração Z:**  
  Desenvolver programas de engajamento, mentoria e capacitação voltados para os funcionários de 18-25 anos.

- **Promoção de Equidade:**  
  Investigar a diferença salarial identificada para garantir a **equidade na remuneração**.

- **Fortalecimento da Cultura Empresarial:**  
  Reforçar a cultura e os valores da empresa, com ênfase na sua importância para a retenção dos funcionários mais jovens.

---

## 6. Tecnologias Utilizadas
- **Python:** Linguagem de programação principal  
- **Pandas:** Manipulação e análise de dados  
- **Matplotlib & Seaborn:** Criação de visualizações e gráficos
