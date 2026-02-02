# 🚚 Monitoramento de Performance de Entregas

![Capa do Projeto](images/print_principal.png)

## 💼 O Problema de Negócio

A empresa gerenciava um alto volume de operações (54 mil entregas) mas carecia de visibilidade sobre a pontualidade por região e canal. A dificuldade em identificar gargalos específicos (cidades ou vendedores com baixo desempenho) impedia a tomada de decisão ágil para reduzir os atrasos e melhorar o nível de serviço.

## 🎯 Objetivo

Desenvolver um painel gerencial para monitorar o status das entregas e a performance das equipes, permitindo uma visão detalhada dos ofensores de prazo e a eficiência da distribuição logística.

## 🛠️ Tecnologias Utilizadas

* **Power BI:** Visualização e interatividade.
* **Power Query:** Limpeza e transformação de dados (ETL).
* **DAX:** Cálculos para categorização de status (Antecipado/Atrasado) e contagens agregadas.
* **Modelagem de Dados:** Esquema Star Schema (Fato/Dimensão).

## 📊 Principais KPIs e Métricas

* **Volume Total de Entregas:** Monitoramento da carga total e sazonalidade mensal.

* **Entregas no Prazo:** Total absoluto de entregas que cumpriram o acordo de nível de serviço (47 Mil).

* **Status de Entrega:** Breakdown percentual entre Antecipado (70%), No Prazo e Atrasado.

* **Performance por Canal/Equipe:** Comparativo de volume entregue por canais de venda e regiões geográficas.

## 🚀 Resultados e Insights

1.  **Otimização de SLA:** Identificou-se que **70,7%** das entregas são antecipadas, indicando oportunidade para ajustar a promessa de prazo ao cliente e tornar o frete mais competitivo.

2.  **Foco em Gargalos:** Mapeamento de cidades críticas (ex: Cidade 79 com maior volume absoluto de atrasos) para atuação direta da gestão.

3.  **Análise Sazonal:** Visualização clara da variação de volume no mês de setembro, permitindo investigação de causas operacionais.

---

*Este projeto foi desenvolvido como parte do curso de Power BI da Data Science Academy.*
