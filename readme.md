# README - Serviço de Corrida por Aplicativo

Este é um projeto apresentado como solução de uma prova de Programação Orientada a Objetos (POO) para um serviço de corrida por aplicativo. Ele consiste em uma pequena aplicação Python que contém quatro classes: Corrida, Viagem, Pagamento e Motorista.

Funcionamento da aplicação
Ao ser executada, a aplicação solicita ao usuário as informações necessárias para criar um objeto Corrida, um objeto Viagem e um objeto Pagamento, que serão utilizados para criar um objeto Motorista e adicionar uma corrida ao registro de corridas desse motorista.

O objeto Corrida contém valores relacionados à corrida (forma de pagamento, tempo e distância) e métodos de cálculo do valor de cada corrida. O objeto Viagem encapsula dados que são relacionados a cada corrida (distância, valor da viagem, origem e destino). O objeto Pagamento contém atributos relacionados ao método e valores dos pagamentos. Por fim, o objeto Motorista possui atributos e métodos pertinentes ao objeto motorista e registra os dados pertinentes a cada corrida em um dicionário.

Ao final da execução, é possível consultar o registro de corridas de um motorista e o valor total líquido recebido por ele.

#Instruções de uso
Clone o repositório ou baixe o arquivo zip e descompacte-o.
Certifique-se de ter o Python 3.x instalado na sua máquina.
Abra o terminal ou prompt de comando e navegue até o diretório onde está a aplicação.
Execute o comando python projpoo.py para rodar a aplicação.
Siga as instruções exibidas no terminal para inserir as informações necessárias.
Ao final, será exibido o registro de corridas e o valor total líquido recebido pelo motorista.


#Observações
As informações fornecidas pelo usuário são validadas através de métodos específicos em cada classe.
O valor da corrida é calculado levando em consideração a distância e o tempo rodados, com um valor base definido por km e por hora rodados.
O valor final da corrida pode sofrer desconto de acordo com o método de pagamento escolhido.
O registro de corridas é armazenado em um dicionário, com um ID de corrida gerado aleatoriamente como chave.
O valor total líquido recebido por um motorista é obtido somando os valores recebidos em cada corrida registrada no dicionário.
Neste projeto não são utilizados conceitos de herança e privacidade de métodos e atributos, propositalmente porque fazia parte da questão a solução sem utilização destes.





