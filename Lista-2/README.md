# Coursera - USP - Processamento Neural de Linguagem Natural em Português I
![Coursera-USP-PLN-Logo](../Coursera-USP-PLN-Logo.png "Coursera-USP-PLN-Logo")

## Lista 2 - NN & Backpropagation

Tópicos:
- Perceptron;
- Aprendizado de uma função linear;
- Aprendizado de uma função não linear;
- Prevendo se vai chover na Austrália.


Questões:
1) Defina as camadas para esta rede neural e treine seu modelo, 
   note que a saída unitária não deve ter função de ativação (por que?).
2) Faça modificações e veja os resultados
    - O que acontece se você muda as funções de ativação? 
      Teste algumas diferentes e descreva seus resultados, em especial a tangente hiperbólica.
    - O que acontece se você mudar a função de otimização? 
      Teste diferentes funções e descreva seus resultados, em especial as funções SDG e RMSprop.
    - Volte a primeira parte desse notebook 
      e troque a função de ativação da rede de uma camada (pérceptron) de sdg para adam, o que acontece?
    - A avaliação de performance que realizamos foi apenas para pontos contidos no mesmo intervalo que o conjunto de treino, 
      ou seja, foi apenas uma interpolação. Sem alterar sua rede repita o teste realizando uma extrapolação, 
      com pontos fora do intervalo [0;10] e descreva seus resultados.
      O que aconteceu com a performance?
3) Complete as funções aqui descritas seguindo a assinatura sugerida para separar em treino e teste, 
   de uma olhada na função train_test_split() do Scikit-Learn.
4) Agora que você ja ganhou uma familiaridade com a API Keras, 
   escreva sozinho do começo ao fim um modelo que ira dizer se amanhã vai chover ou não e avalie sua performance.


## Referências
Coursera - USP - Processamento Neural de Linguagem Natural em Português I:
[https://www.coursera.org/learn/processamento-neural-linguagem-natural-em-portugues-i](https://www.coursera.org/learn/processamento-neural-linguagem-natural-em-portugues-i)

Lista 2 - NN & Backpropagation:
[https://colab.research.google.com/github/alan-barzilay/NLPortugues/blob/master/Semana%2002/02%20-%20NN%20_%20Backpropagation.ipynb](https://colab.research.google.com/github/alan-barzilay/NLPortugues/blob/master/Semana%2002/02%20-%20NN%20_%20Backpropagation.ipynb)

Build Your First Neural Network with Pytorch: [https://curiousily.com/posts/build-your-first-neural-network-with-pytorch/](https://curiousily.com/posts/build-your-first-neural-network-with-pytorch/)

TensorFlow 2.0: [www.tensorflow.org](https://www.tensorflow.org)

Kaggle - Rain in Australia - Weather dataset rattle package: [https://www.kaggle.com/jsphyg/weather-dataset-rattle-package](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)