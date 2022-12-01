### Avaliação 

Esse repositório contém dois arquivos Jupyter Notebook com as resoluções das questões solicitadas. O primeiro deles se refere ao treinamento usando Bag of Visual Words e três redes de classificação: SVM, KNN e Logistic Regression. Features são extraidas utilizando o descritor ORB. Foi realizado um treinamento com todos os dados. No entanto, o resultado não foi satisfatório; a rede não conseguiu convergir. Tentei relizar novos ajustes (tunning de modelo, aumento da cluster, uso de outro extrator de features - SIFT), mas a demora no processamento é considerável, impactando no tempo. Quando realizado o treinamento com apenas duas classes, há um bom resultado no modelo. Desse modo, realizei o treinamento com duas classes: gato e cachorro. 

No segundo notebook, é removida a camada Fully-Connected e somente utilizado o encoding da rede pré-treinada com o ImageNet. As features são extraidas a partir dessa CNN e usadas como input nas redes usadas no primeiro arquivo.


Melhores resultados foram obtidos usando a CNN. Como pedido, as métricas de avaliação foram executadas para mostrar o desempenho do modelo quanto a classificação.