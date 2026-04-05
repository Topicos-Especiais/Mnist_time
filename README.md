Nosso objetivo é elaborar um modelo de rede de perceptrons para reconhecer caracteres da base MNIST. O perceptron é o tipo mais simples de rede neural artificial feedforward com múltiplas camadas, nelas haverá várias entradas que se combinam em um único sinal de saída. Essa combinação é calculada como uma soma ponderada da combinação das entradas. 

Iremos comparar 3 formas de fazer o trabalho com diferentes bibliotecas python: com pytorch, com tensorflow e com scikit-learn.


Parâmetros Padronizados: 
- entrada = 784 
- ⁠número de camadas ocultas = 2
- ⁠neurônios por camada oculta = 256 (na primeira) e 128 (na segunda).
- Função de ativação = ReLu
- ⁠otimizador = Adam
- ⁠taxa de aprendizado = 0.001
- ⁠tamanho do batch = 256
- ⁠número de épocas = 50
- ⁠função de perda = sparse_categorical_crossentropy
- ⁠dados de treinamento/ validação = : MNIST (Keras), com 20% dos dados de treino reservados para validação
