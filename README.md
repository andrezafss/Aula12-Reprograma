# Aula12-Reprograma
Banco de Dados

## Banco de Dados
Se trata de uma coleção de informações que se relacionam de modo que criem algum sentido, isto é, é uma estrutura bem organizada de dados que permite a extração de informações.

## Banco de Dados Não Relacional
Diferentemente dos bancos relacionais, a estrutura de dados não precisa ser definida previamente, portanto, em uma mesma tabela pode-se ter dados com propriedades diferentes.

## MongoDb
É uma nova ideia de banco de dados trazendo conceitos de Banco de Dados Orientado à Documentos, que tem como característica conter todas as informações importantes em um único documento, ser livre de esquemas, possuir identificadores únicos universais, possibilitar a consulta de documentos através de métodos avançados de agrupamentos e filtragem.

## Comandos

### * use 
Cria um banco de dados novo.

### * show databases
Mostra os bancos de dados que existem em um servidor.

### * db.dropDatabase()
Remove o banco de dados atual.

### * db.createCollection(<NOme da Collection>)
Cria uma collection (array de documentos)

### * show collections
Lista todas as collections.

### * db.<NomeDaCollection>.find()
Busca todos os registros de uma collection.

### * db.<NomeDaCollection>.find().pretty()
Mostra o retorno de forma mais amigável.

### * db.<NomeDaCollection>.findOne()
Retorna apenas um único registro(o primeiro registro).

### * db.<NomeDaCollection>.insertOne({<atributos>})
Inclue um registro dentro de uma collection.

### * db.<NomeDaCollection>.insertMany([{//objetos a serem inseridos//}])
Inclue vários registros de uma única vez.
