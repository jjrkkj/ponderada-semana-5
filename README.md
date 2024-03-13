# Ponderada da semana 5 - "Elaboração de aplicação integrada a um banco de dados"

Este repositório contém um vídeo demonstrativo que explica o processo de elaboração de uma aplicação integrada a um banco de dados hospedado na AWS. O objetivo do projeto foi criar uma instância EC2 para hospedar tanto o frontend quanto o backend da aplicação, que se conecta a um banco de dados RDS MariaDB.

## Vídeo Explicativo🎬
O vídeo disponível neste repositório detalha o passo a passo da construção da aplicação, desde a configuração dos recursos na AWS até a implementação do código para interação com o banco de dados.

<a href='./video'>Link para o vídeo</a>

## Detalhes da Aplicação 💻
A aplicação foi desenvolvida utilizando a linguagem PHP para o backend e frontend. O arquivo SamplePage.php, criado ao seguir o tutorial "https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/CHAP_Tutorials.WebServerDB.CreateWebServer.html", contém o código responsável por apresentar a página web aos usuários e processar os dados enviados pelo formulário.

## Banco de Dados na RDS 🗃️
O banco de dados utilizado foi o MariaDB hospedado na Amazon RDS. Foi criada uma instância de banco de dados com o nome "sample" e uma tabela chamada "EMPLOYEES", que possui as seguintes colunas:

1. id (INT) - Identificador único da pessoa.
2. name (VARCHAR) - Nome da pessoa.
3. address (VARCHAR) - Endereço da pessoa.
4. age (INT) - Idade da pessoa.
5. famous (BOOLEAN) - Indica se a pessoa é famosa ou não.

## Considerações Finais ❗
A construção desta aplicação envolveu a configuração cuidadosa dos recursos na AWS, a reestruturação do código, a integração entre o frontend e o backend e muito aprendizado. Obrigado pela atenção! ❤️
