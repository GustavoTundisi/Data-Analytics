# 🧠 Segmentação de Clientes com Machine Learning

![Capa do Projeto](images/print_principal.png)

## 💼 O Problema de Negócio
A abordagem de marketing da empresa era genérica ("spray and pray"). O objetivo era identificar grupos de clientes com comportamentos de compra similares para criar estratégias de personalização e retenção, visando aumentar o LTV (Lifetime Value).

## 🎯 Objetivo
Implementar um algoritmo de Clusterização (K-Means) integrado ao Power BI para agrupar clientes matematicamente, eliminando a segmentação baseada apenas em "achismos".

## 🛠️ Tecnologias Utilizadas
* **Power BI:** Interface para o usuário final.
* **Python:** Script de execução do algoritmo de Machine Learning (K-Means).
* **Estatística:** Aplicação de análise RFM (Recência, Frequência, Monetário).

## ⚙️ Como Funciona
1.  O Power BI envia os dados brutos para o script Python.
2.  O algoritmo processa as variáveis e define a qual "Cluster" (grupo) cada cliente pertence.
3.  Os dados retornam ao Power BI já classificados para visualização.

## 🚀 Resultados e Insights
* **Cluster 1 (VIPs):** Clientes com alta frequência e alto ticket médio. Ação sugerida: Programas de fidelidade.
* **Cluster 2 (Em Risco):** Clientes que compravam muito, mas pararam (Recência alta). Ação sugerida: Campanhas de reativação.
* **Cluster 3 (Novos/Baixo Valor):** Clientes esporádicos. Ação sugerida: Ofertas de entrada.

---
*Este projeto foi desenvolvido como parte do curso de Power BI da Data Science Academy, com adaptações focadas em resolução de problemas de negócio.*
