# Projeto-de-Movimento-em-plano-2D-Python
Movimento em plano 2D em Python
-Gabriel 
-Marcos


Neste projeto, o objetivo é implementar uma função em Python capaz de gerar comandos de movimento
para um robô em um plano bidimensional.
O robô possui a posição atual e a posição desejada, ambas representadas por tuplas contendo três valores:
posição em x, posição em y e orientação (yaw). A partir dessas informações, a função deve calcular como o
robô deve se mover para se aproximar da posição desejada.
A função deve receber como entrada:
Uma tupla representando o estado atual do robô: (x_real, y_real, yaw_real);
Uma tupla representando o estado desejado: (x_target, y_target, yaw_target).
Ambas coordenadas no frame do mundo
A função deve retornar:
Uma lista contendo os comandos de velocidade do robô, no formato [vx, omega], onde:
vx representa a velocidade linear (no frame do robô);
omega representa a velocidade angular.

É importante destacar que essa função será chamada a cada instante de tempo. Portanto, os valores de
velocidade são ser recalculados continuamente com base no estado atual do robô, permitindo que ele corrija
sua trajetória ao longo do tempo.
A forma como esses valores serão calculados

ca a critério do aluno, desde que o comportamento resultante

faça com que o robô se mova em direção ao estado desejado.
Este projeto tem como objetivo consolidar o uso de funções, manipulação de tuplas, retorno de múltiplos
valores e organização de código, a partir de uma aplicação prática.