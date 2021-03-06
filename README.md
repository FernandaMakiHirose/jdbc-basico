 # Trabalhando com banco de dados usando JDBC
1- <a href="https://dev.mysql.com/downloads/workbench/">instalar MySQL e MySQL Workbench.</a> <br>
2- clique no ‘local instance’ para criar banco de dados. <br>
3- Crie um banco de dados e uma tabela no MySQL com as informações correspondentes ao código. <br>
4- Baixar driver do MySQL (No build.gradle foi adicionado o código da linha 15 e 16 do projeto). <br>
5- Criar uma url (string de conexão) com os seguintes parâmetros: driver, endereço do BD e nome do BD (No arquivo ConnectionJDBC.java). <br>
6- Criar uma connection através do DriverManager utilizando o método getConnection, passando os parâmetros: string de conexão, usuário e senha.

## Pré-requisitos 
- Java Development Kit (JDK) – 1.8 ou superior.
- IntelliJ IDEA (É recomendável seguir com essa IDE, porém pode ser selecionada outra). <br>
- Gradle 5.3.1 (É utilizado para baixar o Driver JDBC. Se quiser, pode ser instalado manualmente ou com o Maven). <br>
- <a href="https://github.com/danielkv7/jdbc-basico/blob/master/src/main/java/part1/DatabaseInstructions">MySQL (Passos para instalação estão no arquivo "DatabaseInstructions.</a>

## Licença
Distribuido sob a licença MIT License. Veja `LICENSE` para mais informações.

## JDBC e Drivers de Conexão
- JDBC (java database connectivity) é uma API com diversas classes e interfaces escritas na linguagem Java que estão presentes nos pacotes java.sql e javax.sql. elas permitem que programas java realizem conexões em banco de dados para realizar consultas. uma dessas classes principais é o driver JDBC que intermedia essa interação.
- sem a API JDBC seria necessário conhecer o protocolo proprietário de cada banco de dados para se conectar e realizar consultas. já com a API JDBC, é utilizada somente uma interface java para qualquer banco de dados, deixando o driver implementar as especificações de cada banco de dados, enquanto o desenvolvedor se preocupa apenas em selecionar um driver e criar as queries (neste caso, consultas sql).

## Executar
Basta rodar a função main em um dos seguintes arquivos:
- <a href="https://github.com/FernandaMakiHirose/jdbc-basico/blob/main/src/main/java/part2/ConnectionJDBC.java">ConnectionJDBC.java.</a> <br>
- <a href="https://github.com/FernandaMakiHirose/jdbc-basico/blob/main/src/main/java/part3/QueriesExecution.java">QueriesExecution.java.</a> <br>

## Sobre a Autora
Oi, eu sou a Fernanda! Estou aqui para contribuir com meu conhecimento e espero poder ajudar no desenvolvimento profissional de cada um de vocês.

[![Linkedin Badge](https://img.shields.io/badge/-Fernanda_Maki_Hirose-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)](https://www.linkedin.com/in/fernanda-maki-hirose-801117208/)  [![Gmail Badge](https://img.shields.io/badge/-femahi2020@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:femahi2020@gmail.com)](mailto:femahi2020@gmail.com)
