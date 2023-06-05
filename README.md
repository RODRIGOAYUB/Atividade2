# Atividade2

Para executar o programa, siga os seguintes passos:

1 - Abra um terminal e navegue até o diretório onde você salvou o arquivo bookstoreapplication.java.

2 - Execute o seguinte comando para compilar e empacotar o projeto em um arquivo JAR:
mvn package

3 - Após o comando ser concluído com sucesso, você verá um arquivo JAR criado no diretório target do projeto, com o nome bookstore-1.0.0.jar (ou similar).

4- Execute o seguinte comando para iniciar o servidor da aplicação Spring Boot:
java -jar target/bookstore-1.0.0.jar

O servidor da aplicação será iniciado e você poderá acessar a API RESTful de gerenciamento de livros em

http://localhost:8080/books.

Listar todos os livros: GET http://localhost:8080/books

Buscar livro por ID: GET http://localhost:8080/books/{id}

Inserir um novo livro: POST http://localhost:8080/books

Atualizar um livro existente: PUT http://localhost:8080/books/{id}

Remover um livro: DELETE http://localhost:8080/books/{id}
