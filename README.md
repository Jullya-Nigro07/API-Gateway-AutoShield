# API Gateway - AutoShield

---
API Gateway do AutoShield, responsável por receber as requisições e encaminhá-las para os microsserviços da aplicação.

## Dependência

O Gateway utiliza o Eureka Server para descobrir os microsserviços registrados.

Eureka Server: https://github.com/Jullya-Nigro07/AutoShield.git

## Como executar
- Rode primeiro o Eureka Server.
- Acesse http://localhost:8761 e verifique se o servidor está funcionando.
- Inicie os microsserviços que serão utilizados pelo Gateway.
  - https://github.com/Jullya-Nigro07/Microservice-Cliente-AutoShield.git
- Execute esta aplicação.

O Gateway utiliza o Service Discovery do Eureka para localizar os microsserviços e encaminhar as requisições para eles.