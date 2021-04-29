# heroes-springwebflux-API
API de gerenciamento de heróis para o projeto da digital innovation one.

# Demo sobre live coding da digital innovation one - spring webflux - criando seu gerenciador de herois

## Stack utilizada
* Java8
* spring webflux
* Spring data
* dynamodb
* junit
* sl4j
* reactor

### Executar dynamo:
Abrir terminal e executar dentro da pasta em que o jar está baixado:

comando para subir o banco local: java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb

comando para listar as tabelas criadas: aws dynamodb list-tables --endpoint-url http://localhost:8000

documentacao gerada pela aplicação: swagger: http://localhost:8080/swagger-ui-heroes-reactive-api.html
