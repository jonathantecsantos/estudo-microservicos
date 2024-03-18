# estudo-microservicos
Repositório de estudos de microserviços Java


Criei um cenário bacana de estudo disponibilizando microserviços que são requisitados através de um Gateway (que também é um microserviço). Através do serviço do Eureka Discovery também consigo observar todos os microserviços registrados e com o Load Balance controlar o redirecionamento das requisições.

Para finalizar, configurei um Circuit Breaker com o Resilience4j para controlar/monitorar os estados da aplicação, evitando falhas de comunicações com serviços inoperantes.

API de Pedidos: https://github.com/jonathantecsantos/api-pedidos
API de Pagamentos: https://github.com/jonathantecsantos/microservicos
API do Gateway: https://github.com/jonathantecsantos/api-gateway
API do Eureka Server: https://github.com/jonathantecsantos/eurekaserver
