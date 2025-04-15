# 🛍️ Análise de Desempenho das Lojas - Alura Store

Este projeto foi desenvolvido como parte do desafio de Data Science da Alura. O objetivo principal foi analisar o desempenho de quatro lojas virtuais da rede **Alura Store**, utilizando Python e bibliotecas de análise de dados.

## 📌 Objetivo

O desafio era identificar **qual loja possui o pior desempenho** e, com base em dados reais, recomendar sua venda.

---

## 🔍 Etapas da Análise

### 1. Faturamento Total
Calculei o total de vendas (faturamento) de cada loja, somando os valores dos produtos vendidos.


### 2. Categoria mais Vendida
Juntei todas as lojas e contei quantos produtos de cada categoria foram vendidos, para entender o comportamento do cliente.

### 3. Média de Avaliação
Analisei a média das avaliações de compra feitas pelos clientes, como um indicador de satisfação.

### 4. Produtos Mais e Menos Vendidos
Identifiquei os produtos mais e menos populares.

### 5. Frete Médio
Calculei o valor médio pago em frete por loja para entender o impacto logístico nos resultados.

### 6. Resultado
Juntei as métricas principais:
	•	Faturamento
	•	Avaliação média
	•	Frete médio
	•	Diversidade de produtos

Depois, normalizei os dados com MinMaxScaler para comparar de forma justa. Invertemos o frete (quanto menor, melhor) e calculamos uma pontuação final média.
Com base nos dados analisados e normalizados, conseguimos encontrar de forma justa e objetiva qual loja tem o pior desempenho geral. Essa abordagem pode ser usada em outras situações reais de negócio. A loja com a menor pontuação final foi recomendada para venda.

