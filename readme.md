# **Estudo voltado para algoritmos de aprendizado supervisionado: Árvores de Decisão, KNN e SVM.**

Os algoritmos de classificação são técnicas de Machine Learning utilizadas para atribuir rótulos ou categorias a conjuntos de dados. Os algoritmos de Árvore de Decisão, K-Nearest Neighbors (KNN) e Support Vector Machine (SMM) se enquadram nessa classe de algoritmos de classificação. Todos têm como característica comum a análise de exemplos previamente rotuladas para detectar padrões e, a partir deles, determinam em qual classe um novo elemento de teste pertencerá. Vale ressaltar que esses algoritmos têm várias aplicações, desde reconhecimento de imagens, filtragem de dados, sistemas de recomendação ou até mesmo diagnósticos médicos. Dessa forma, o presente estudo visa aprofundar o conhecimento nesses algoritmos e aplicá-los para um problema proposto e, em seguida, analisar um data-set com informações sobre câncer para classificar o tipo de tumor.

## Objetivos
1. Desenvolver uma árvore de decisão para ajudar uma pessoa decidir entre diferentes hobbies ou carreiras.
2. Explorar um dataset para criar uma nova aplicação utilizando os algoritmos de aprendizado supervisionado. Especificamente, a abordagem neste projeto trata-se de uma análise de dados sobre câncer de mama que foram utilizados para classificar o diagnóstico.


## **Objetivo 1 - Árvore de Decisão: Decidir entre diferentes Hobbies.**
As árvores de decisão são estruturas utilizadas para tomada de decisão e resolução de problemas. Elas funcionam como um fluxo de perguntas que, com base nas respostas obtidas, direcionam para uma conclusão ou recomendação específica. Em cada nó da árvore, é feita uma pergunta que separa os possíveis caminhos levando a novas perguntas ou a um resultado final.
Essa abordagem  permite que decisões mais complexas sejam divididas em etapas um pouco mais simples e sequenciais. Dessa forma, com a implementação de uma árvore de decisão, é possível criar um sistema simples de recomendação, como é o caso abordado para decidir entre diferentes hobbies e carreiras.

Para modelar a árvore de decisão, foram consideradas as seguintes perguntas:
1. Você gosta de trabalhar em equipe?
2. Prefere atividades ao ar livre?
3. Gosta de lidar com números?
4. Gosta de atividades de alta intensidade?
5. Se sente confortável com tecnologia?
6. Gosta de desafios lógicos?
7. Prefere atividades artísticas?
8. Você curte praticar corrida ou musculação?
9. Prefere atividades moderadas, como escalada ou caminhada?
10. Você se interessa por jogos e desafios digitais?
11. Prefere atividades artísticas em grupo, como música ou teatro?
12. Você se vê atuando em áreas de tecnologia e programação?
13. Prefere carreiras voltadas para engenharia ou matemática?
14. Você se interessa por música e artes visuais?
15. Prefere atividades solitárias, como leitura ou jogos solo?

Obs.: Inicialmente a proposta eram 10 perguntas, mas a quantidade foi ajustada para acrescentar novos resultados para a árvore de decisão.

As decisões de implementação e detalhes sobre o algoritmo aplicado está no arquivo [hobbies.ipynb](hobbies.ipynb).

## **Objetivo 2 - Classificação de Diagnóstico de Câncer**

Breast Cancer Wisconsin (Diagnostic): Um conjunto de dados de câncer de mama, com 30 características numéricas, classificando os tumores em malignos e benignos.
Link para o dataset: [Breast Cancer Dataset](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

### Explicando o dataset:
O Breast Cancer Wisconsin Dataset (diagnóstico) é um conjunto de dados utilizado para classificar tumores mamários como benignos ou malignos. O dataset contém 569 instâncias, com 30 atributos numéricos extraídos de imagens digitalizadas de células cancerígenas. Esses atributos representam características como a textura, área e perímetro das células. O objetivo principal desse estudo é utilizar esse conjunto de dados para desenvolver e testar algoritmos de classificação, de modo a identificar se o tumor é benigno ou maligno. Para essa tarefa, foram aplicados três algoritmos: Árvore de Decisão, K-Nearest Neighbors (KNN) e Máquina de Vetores de Suporte (SVM).

### Implementação e comparação dos algoritmos
A implementação e comparação da árvore de decisão, do KNN e do SVM estão no arquivo [cancer_diagnostic.ipynb](cancer_diagnostic.ipynb). 


## Acesso ao Jupyter Notebook de cada proposta
- [Árvore de Decisão: Decidir entre diferentes Hobbies](hobbies.ipynb).
- [Classificação de Diagnóstico de Câncer](cancer_diagnostic.ipynb). 


## Autores
- **Anielly Gonçalves**: anielly@aluno.cefetmg.br
- **Emanuel Vieira Tavares**:emanuel@aluno.cefetmg.br 

  DECOM-DV/CEFET-MG.
  2024/2.
