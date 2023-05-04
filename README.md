<h2>Microserviço de Cadastro de Pessoas e Animais</h2>
Este projeto consiste em um microserviço de cadastro de pessoas e animais que utiliza o Eureka Server e o Zuul Service para vincular todos os serviços em uma área de Config Server.

Funcionalidades
O microserviço de cadastro de pessoas e animais possui as seguintes funcionalidades:<br><br>

Cadastro de pessoas
Consulta de pessoas cadastradas
Edição de informações de pessoas cadastradas
Exclusão de pessoas cadastradas
Cadastro de animais vinculados a uma pessoa
Consulta de animais cadastrados vinculados a uma pessoa
Edição de informações de animais cadastrados vinculados a uma pessoa
Exclusão de animais cadastrados vinculados a uma pessoa
Tecnologias utilizadas
O microserviço de cadastro de pessoas e animais foi desenvolvido utilizando as seguintes tecnologias:<br><br>

Java 8
Spring Boot
Eureka Server
Zuul Service
Config Server
MySQL
Como executar o projeto
Para executar o microserviço de cadastro de pessoas e animais, siga as instruções abaixo:<br><br>

Clone este repositório em sua máquina local
Configure o Config Server com as informações do seu ambiente
Configure o Eureka Server com as informações do seu ambiente
Configure o Zuul Service com as informações do seu ambiente
Configure o MySQL com as informações do seu ambiente
Execute o microserviço de cadastro de pessoas e animais
Configurando o Config Server
O Config Server é responsável por armazenar as configurações dos serviços utilizados no projeto. Para configurá-lo, siga as instruções abaixo:<br><br>

Acesse a pasta config-server do projeto
Abra o arquivo application.yml
Configure as informações do seu ambiente (ex: porta, endereço do servidor MySQL, nome do banco de dados, usuário e senha)
Configurando o Eureka Server
O Eureka Server é responsável por gerenciar os serviços que estão em execução. Para configurá-lo, siga as instruções abaixo:<br><br>

Acesse a pasta eureka-server do projeto
Abra o arquivo application.yml
Configure as informações do seu ambiente (ex: porta)
Configurando o Zuul Service
O Zuul Service é responsável por rotear as requisições para os serviços corretos. Para configurá-lo, siga as instruções abaixo:<br><br>

Acesse a pasta zuul-service do projeto
Abra o arquivo application.yml
Configure as informações do seu ambiente (ex: porta, endereço do Eureka Server)
Configurando o MySQL
O MySQL é responsável por armazenar os dados dos serviços. Para configurá-lo, siga as instruções abaixo:<br><br>

Crie um banco de dados com o nome "cadastro_pessoas_animais"
Configure o usuário e senha de acesso ao banco de dados
Executando o microserviço de cadastro de pessoas e animais
Para executar o microserviço de cadastro de pessoas e animais, siga as instruções abaixo:

Acesse a pasta cadastro-pessoas-animais do projeto
Abra o arquivo application.yml
Configure as informações do seu ambiente (ex: porta, endereço do Eureka Server, endereço do Config
