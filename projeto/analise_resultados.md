# Etapa 5 - ANÁLISE DOS RESULTADOS

# Relatório do Trabalho: Análise de Desempenho com Árvores de Decisão  

Após a aplicação de diferentes abordagens para resolver o problema de classificação, optamos pelo uso do algoritmo de **Árvore de Decisão** devido à sua capacidade de gerar modelos interpretáveis e identificar os principais fatores que impactam o resultado da classificação.  

---

## **Etapas Realizadas**  

1. **Métricas de Avaliação:**  
   - Calculamos as principais métricas, incluindo:  
     - **Acurácia:** Mediu a proporção de predições corretas.  
     - **Taxa de Erros:** Avaliou as predições incorretas em relação ao total.  
     - **Matriz de Confusão:** Permitiu a análise detalhada das classificações corretas e incorretas para cada classe (alfabetizado e não alfabetizado).  

2. **Interpretação dos Resultados:**  
   - Identificamos as variáveis mais relevantes que impactam a alfabetização, como *"Total de não alfabetizados"* e *"Renda média"*.  
   - Avaliamos o impacto de diferentes parâmetros do modelo, como a profundidade máxima da árvore e os critérios de divisão (Gini e Entropia).  
   - Observamos que o ajuste dos parâmetros para evitar sobreajuste (como limitar a profundidade da árvore) resultou em modelos mais robustos.  

3. **Desempenho do Algoritmo:**  
   - A **Árvore de Decisão** apresentou resultados satisfatórios, com uma **alta acurácia** em identificar as classes.  
   - **Vantagens:** A transparência do modelo facilitou a explicação dos resultados, mostrando claramente os critérios usados para classificar cada grupo.  
   - **Limitações:** A árvore pode ser sensível a outliers ou ruídos, o que exige maior atenção na preparação dos dados.  

4. **Exploração dos Dados:**  
   - Durante a análise inicial, destacamos algumas características interessantes, como:  
     - Regiões com maior proporção de não alfabetizados tendem a ter menor diversidade de renda.  
     - Grupos classificados como alfabetizados apresentaram menor variância em indicadores econômicos.  

---

## **Conclusão**  

A **Árvore de Decisão** se mostrou eficiente para o conjunto de dados analisado, permitindo não apenas uma classificação precisa, mas também o entendimento das variáveis mais relevantes para o problema. As configurações ideais para o modelo foram alcançadas com ajustes nos parâmetros, resultando em predições consistentes e interpretáveis. Esses resultados destacam a importância de explorar os dados e ajustar os modelos para extrair insights valiosos e melhorar a 
performance.  

## **Link para o Google Colab**  
Google Colab clicando [aqui](https://colab.research.google.com/drive/1sTAxf5Ix5FmJ5TMNNsyFu8XbaGg6jOd9?authuser=1#scrollTo=NFHRVPkArbLO).  






