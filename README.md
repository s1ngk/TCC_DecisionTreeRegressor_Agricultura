# A Inteligência Artificial na Previsão da Produtividade do Agronegócio: Um Estudo de Caso 
Dicentes:
[@lucasoriental](https://github.com/lucasoriental) [@theraulsena](https://github.com/Theraulsena) [@s1ngk](https://github.com/s1ngk)

Dataset utilizado: https://www.kaggle.com/datasets/samuelotiattakorah/agriculture-crop-yield/data

# Resumo

Neste artigo, foi explorada a aplicação do modelo Decision Tree Regressor na previsão da produção agrícola (em toneladas por hectare), com base em variáveis categóricas e contínuas. O estudo utilizou um dataset público coletado no Kaggle e bibliotecas populares como Pandas, NumPy e Scikit-learn para a análise e modelagem dos dados. O modelo foi treinado e avaliado com dados históricos, que incluíram informações sobre tipo de solo, condições climáticas e região geográfica. O código desenvolvido foi hospedado no GitHub. Este trabalho destaca o potencial da Inteligência Artificial no agronegócio, contribuindo para o planejamento e a tomada de decisões no setor. 

# Introdução

Nos últimos anos, a crescente demanda por alimentos tem desafiado a capacidade do setor agrícola, e o Brasil, como uma das principais potências agrícolas, desempenha um papel crucial nesse cenário. Em 2022, o agronegócio representou 25,2% do PIB brasileiro (CEPEA, 2023), reforçando sua importância econômica. Para manter sua posição no mercado internacional, é essencial adotar inovações tecnológicas que otimizem a produção agrícola. 

Nesse contexto, a Inteligência Artificial (IA) surge como uma ferramenta estratégica, com o aprendizado de máquina (machine learning) se destacando como uma técnica essencial para prever rendimentos e analisar padrões nos dados agrícolas. O uso de algoritmos como o Decision Tree Regressor tem sido promissor para prever a produtividade agrícola, considerando variáveis climáticas, características do solo e práticas de manejo. 

Este trabalho busca explorar o uso do Decision Tree Regressor na previsão da produtividade agrícola, analisando os principais fatores que impactam os rendimentos e informações relevantes para apoiar decisões no setor. A pesquisa inclui uma revisão sobre IA e aprendizado de máquina, detalhando a implementação do algoritmo e discutindo seus resultados, com o objetivo de demonstrar como a tecnologia pode promover soluções inovadoras e sustentáveis para os desafios do agronegócio. 

# Conclusão

O estudo abordou desde a análise e pré-processamento dos dados até a avaliação e otimização do modelo, seguindo um fluxo estruturado que incluiu: criação de variáveis dummies, remoção de outliers, amostragem estratificada, ajuste de hiperparâmetros via GridSearchCV, e validação cruzada. 

Os resultados obtidos demonstraram que o modelo conseguiu produzir previsões com desempenho aceitável na maioria dos casos, evidenciado por uma média da margem de erro de 11,22% e uma diferença média de 0,0013 pontos entre os valores reais e previstos. No entanto, também foi observado que erros mais elevados ocorreram em casos isolados, sobretudo devido às limitações impostas pela natureza sintética do dataset, pela ausência de correlações reais e pela complexidade intrínseca do problema, como a interação de múltiplos fatores climáticos, ambientais e de manejo agrícola. 

Apesar das limitações, o estudo alcançou seu objetivo principal de implementar, avaliar e discutir o desempenho de um modelo preditivo para produtividade agrícola, fornecendo uma base inicial para trabalhos futuros nessa área. 

## Sugestões para Trabalhos Futuros

A continuação deste trabalho pode explorar diversas direções para aprimorar os resultados obtidos e expandir a compreensão sobre a previsão de produtividade agrícola. Primeiramente, seria interessante realizar uma análise mais profunda sobre a qualidade dos dados sintéticos utilizados, considerando a possibilidade de gerar um conjunto de dados mais representativo e realista, que possa oferecer uma base mais sólida para o treinamento dos modelos. 

Outra área que pode ser abordada é a experimentação com modelos de aprendizado de máquina mais complexos, como redes neurais ou modelos de ensemble, que possuem maior capacidade de capturar interações não lineares e padrões complexos nos dados. Além disso, seria relevante integrar dados ambientais e climáticos reais, como informações sobre temperatura, umidade e precipitação, para melhorar ainda mais a precisão das previsões. 

Também é importante explorar o impacto de diferentes abordagens de balanceamento de dados, a fim de melhorar a performance do modelo em cenários menos representados. Por fim, uma possível linha de pesquisa seria aplicar técnicas de aprendizado profundo (deep learning) para explorar novas maneiras de modelar as relações entre as variáveis e aumentar a robustez da previsão. 
