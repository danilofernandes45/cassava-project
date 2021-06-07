# Cassava Leaf Disease Classification

Projeto da disciplina de Redes Neurais e Aprendizagem Profunda. Neste projeto foi gerada e treinada uma rede neural convolucional baseada na arquitetura EfficientNetB4 para classificação de doenças que acometiam macaxeiras através de imagens de suas folhagens. Considerando o dataset fornecido, cada instância pode pertencer a uma dentre cinco classes. Estas classes são Cassava Bacterial Blight (CBB), Cassava Brown Streak Disease (CBSD), Cassava Green Mottle (CGM), Cassava Mosaic Disease (CMD) e Healthy, onde as quatro primeiras são doenças.

A fim de melhorar a performance do modelo, foi empregado transfer learning e fine tunning, cujos os valores iniciais dos pesos das camadas convolucionais são aqueles obtidos ao treinar a EfficientNetB4 na base ImageNet. Por fim, obteve-se uma acurácia geral de 0.87.

Link da competição no Kaggle: https://www.kaggle.com/c/cassava-leaf-disease-classification/
