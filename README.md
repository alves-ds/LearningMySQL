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
 `create database cadastro <br>
default character set utf8 <br>
default collate utf8_general_ci;`

## Criar uma tabela com espeficiações quanto ao tipo de variáveis
Para criar uma tabela no nosso banco de dados, especificando as variáveis que serão inseridas nesta tabela e seu respectivo tipo, utilizamos o seguinte comando: <br>
`create table `pessoas` (
`id` int not null auto_increment,
`nome` varchar(30) not null,
`nascimento` date,
`sexo` enum('M', 'F'),
`peso` decimal(5,2),
`altura` decimal(3,2),
`nacionalidade` varchar(20) default 'Brasil',
primary key(id)
) default charset = utf8;` 
