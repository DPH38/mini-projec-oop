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

========= ENGLISH VERSION

README - Ride-hailing App Service

This is a project presented as a solution for an Object-Oriented Programming (OOP) exam for a ride-hailing app service. It consists of a small Python application that contains four classes: Ride, Trip, Payment, and Driver.

Application Functionality
When executed, the application prompts the user for the necessary information to create a Ride object, a Trip object, and a Payment object, which will be used to create a Driver object and add a ride to that driver's ride record.

The Ride object contains values related to the ride (payment method, time, and distance) and methods to calculate the value of each ride. The Trip object encapsulates data that is related to each ride (distance, trip value, origin, and destination). The Payment object contains attributes related to the payment method and value. Finally, the Driver object has attributes and methods relevant to the driver object and records the relevant data for each ride in a dictionary.

At the end of execution, it is possible to consult a driver's ride record and the total net value received by them.

#Instructions
Clone the repository or download the zip file and extract it.
Make sure you have Python 3.x installed on your machine.
Open the terminal or command prompt and navigate to the directory where the application is located.
Run the command "python projpoo.py" to execute the application.
Follow the instructions displayed in the terminal to enter the necessary information.
At the end, the ride record and the total net value received by the driver will be displayed.

#Notes
The user-provided information is validated through specific methods in each class.
The ride value is calculated taking into account the distance and time traveled, with a base value defined per km and per hour traveled.
The final ride value may be discounted according to the chosen payment method.
The ride record is stored in a dictionary, with a randomly generated ride ID as the key.
The total net value received by a driver is obtained by summing the values received in each ride registered in the dictionary.
In this project, concepts of inheritance and method and attribute privacy are not used, intentionally as the question required the solution without these.



