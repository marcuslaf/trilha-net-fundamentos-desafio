# DIO - Trilha .NET - Fundamentos / DIO - .NET Trail - Fundamentals

www.dio.me

---

## Desafio de Projeto / Project Challenge

Para este desafio, voce precisara usar seus conhecimentos adquiridos no modulo de fundamentos, da trilha .NET da DIO.

For this challenge, you will need to use the knowledge acquired in the Fundamentals module of the DIO .NET trail.

---

## Contexto / Context

Voce foi contratado para construir um sistema para um estacionamento, que sera usado para gerenciar os veiculos estacionados e realizar suas operacoes, como por exemplo adicionar um veiculo, remover um veiculo (e exibir o valor cobrado durante o periodo) e listar os veiculos.

You have been hired to build a parking system that will be used to manage parked vehicles and perform operations such as adding a vehicle, removing a vehicle (and displaying the amount charged during the period), and listing vehicles.

---

## Proposta / Proposal

Voce precisara construir uma classe chamada Estacionamento, conforme o diagrama abaixo:

You will need to build a class called Parking, according to the diagram below:

![Diagrama de classe estacionamento / Parking class diagram](diagrama_classe_estacionamento.png)

A classe contem tres variaveis, sendo:

The class contains three variables:

**precoInicial**: Tipo decimal. E o preco cobrado para deixar seu veiculo estacionado. / Decimal type. It is the price charged to park your vehicle.

**precoPorHora**: Tipo decimal. E o preco por hora que o veiculo permanecera estacionado. / Decimal type. It is the price per hour the vehicle will remain parked.

**veiculos**: E uma lista de string, representando uma colecao de veiculos estacionados. Contem apenas a placa do veiculo. / It is a string list, representing a collection of parked vehicles. Contains only the vehicle license plate.

A classe contem tres metodos, sendo:

The class contains three methods:

**AdicionarVeiculo**: Metodo responsavel por receber uma placa digitada pelo usuario e guardar na variavel veiculos. / Method responsible for receiving a license plate entered by the user and storing it in the veiculos variable.

**RemoverVeiculo**: Metodo responsavel por verificar se um determinado veiculo esta estacionado, e caso positivo, ira pedir a quantidade de horas que ele permaneceu no estacionamento. Apos isso, realiza o seguinte calculo: precoInicial + (precoPorHora x horas), exibindo para o usuario. / Method responsible for checking if a given vehicle is parked, and if so, it will ask for the number of hours it remained in the parking lot. After that, it performs the following calculation: precoInicial + (precoPorHora x hours), displaying it to the user.

**ListarVeiculos**: Lista todos os veiculos presentes atualmente no estacionamento. Caso nao haja nenhum, exibir a mensagem "Nao ha veiculos estacionados". / Lists all vehicles currently in the parking lot. If there are none, display the message "No vehicles are parked".

Por ultimo, devera ser feito um menu interativo com as seguintes acoes implementadas:
Finally, an interactive menu should be created with the following actions implemented:

1. Cadastrar veiculo / Register vehicle
2. Remover veiculo / Remove vehicle
3. Listar veiculos / List vehicles
4. Encerrar / Exit

---

## Solucao / Solution

O codigo esta pela metade, e voce devera dar continuidade obedecendo as regras descritas acima, para que no final, tenhamos um programa funcional. Procure pela palavra comentada "TODO" no codigo, em seguida, implemente conforme as regras acima.

The code is halfway done, and you should continue following the rules described above, so that in the end we have a functional program. Look for the commented word "TODO" in the code, then implement according to the rules above.

---

## Tecnologias / Technologies

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

## Autor / Author

Marcus Lafaiete - [@marcuslaf](https://github.com/marcuslaf)
