# dio-transfer-learning
Desafio de Projeto do Bootcamp BairesDev - Machine Learning Practitioner da DIO

Este Notebook realiza o transfer learning de uma rede ImageNet para a classificação de gatos e cachorros. Inicialmente, a rede utilizada não possui as classes "gato" e "cachorro", porém, como é uma rede altamente eficiente para classificação de imagens em geral e treinada com milhões de parâmetros e centenas de milhares de imagens, é possível aproveitar este "conhecimento" para retreinar um dataset menor. Isso é possível porque boa parte dos padrões aprendidos pela rede neural são comuns a qualquer tipo de imagem (identificação de bordas, por exemplo). O retreino foi realizado com o dataset cats_vs_dogs disponível no TensorFlow.

Este trabalho é a entrega do Desafio de Projeto do Bootcamp BairesDev - Machine Learning Practitioner da DIO. Parte dele foi baseado no tutorial disponível em https://colab.research.google.com/github/kylemath/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb.

Toda a descrição do código pode ser visualizada nas célulad do notebook.
