# 🧠 Segmentação de Clientes com Machine Learning

![Capa do Projeto](images/print_principal.png)

## 💼 O Problema de Negócio
A equipe de marketing enfrentava dificuldades em personalizar ofertas, pois não conseguia distinguir padrões claros de consumo apenas olhando para renda ou idade isoladamente. Era necessário entender a relação entre o poder aquisitivo, a idade e a propensão ao gasto (score).

## 🎯 Objetivo
Utilizar algoritmos de Machine Learning para agrupar a base de clientes em clusters matematicamente similares, permitindo a criação de "Personas" baseadas em dados reais para direcionar campanhas mais assertivas.

## 🛠️ Tecnologias Utilizadas
* **Python (Jupyter Notebook):** Ambiente de desenvolvimento para análise exploratória e modelagem.
* **Bibliotecas:** Pandas (manipulação de dados), Scikit-Learn (algoritmo K-Means) e Matplotlib (visualização inicial).
* **Power BI:** Ferramenta de Business Intelligence para construção do dashboard final, storytelling e design.

## ⚙️ Processo de Desenvolvimento
1.  **Modelagem no Jupyter:** Realizei a limpeza dos dados e apliquei o algoritmo K-Means no Jupyter Notebook para identificar os padrões matemáticos e definir os clusters ideais.
2.  **Integração:** Os dados processados e já classificados com seus respectivos "Segmentos" foram exportados e conectados ao Power BI.
3.  **Visualização Final:** No Power BI, foquei na formatação, criação de métricas dinâmicas e design visual para facilitar a leitura executiva dos insights.

## 🚀 Resultados e Insights

A análise identificou 3 perfis distintos de comportamento:

1.  **Segmento 1 - "A Classe Média Gastadora" (Foco Principal):**
    * **Perfil:** Renda Anual mais baixa (média de 52k) e idade avançada (~54 anos).
    * **Insight:** Surpreendentemente, possuem o maior Score de Gastos (54). É o público que mais consome proporcionalmente à renda. Ideal para varejo e promoções de volume.

2.  **Segmento 0 - "A Elite Conservadora":**
    * **Perfil:** Renda Anual altíssima (média de 120k) e idade avançada (~53 anos).
    * **Insight:** Apesar de terem uma renda mais alta, gastam moderadamente (Score 47). Exigem produtos exclusivos ou de investimento, não respondendo bem a apelos de "desconto".

3.  **Segmento 2 - "Os Jovens Poupadores":**
    * **Perfil:** O grupo mais jovem (média de 27 anos) com renda média-alta (82k).
    * **Insight:** Possuem o menor Score de Gastos (43). Provavelmente estão na fase de acumulação de patrimônio. A estratégia deve ser focada em branding e fidelização de longo prazo.

---
*Este projeto foi desenvolvido como parte de um portfólio de Data Analytics, demonstrando proficiência tanto em Python (Back-end da análise) quanto em Power BI (Front-end de negócios).*
