# LearningMySQL
 Arquivos e anotações gerais sobre o meu aprendizado de MySQL. 

 As anotações e práticas deste repositório serão baseadas na playlist [Curso de Banco de Dados MySQL](https://youtube.com/playlist?list=PLHz_AreHm4dkBs-795Dsgvau_ekxg8g1r&si=RLA6Cnr-SxkPjpWh), publicada no canal [Curso em vídeo](https://www.youtube.com/c/CursoemV%C3%ADdeo).

 ## Comando para criar um banco de dados simples
 Para criarmos um banco de dados simples, basta utilizarmos o comando: <br>
 `create database meubanco`

## Comando para apagar um banco de dados
 Para apagarmos um banco de dados, basta utilizarmos o comando: <br>
 `drop database meubanco`

 ## Criar um banco de dados com especificações
 Podemos também criar um banco de dados com especificações relacionadas aos tipos de caracteres que serão utilizados, especificando por exemplo que ele aceite caracteres específicos da língua latina, que envolve pontuações, fazendo as seguintes especificações no momento de criação do banco de dados: <br>
 `create database cadastro
default character set utf8
default collate utf8_general_ci;`
