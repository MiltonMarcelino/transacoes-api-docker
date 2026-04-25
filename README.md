Projeto Docker - API Transações

Este projeto contém:
- MySQL em container
- API Java (Spring Boot)
- API .NET

As aplicações se comunicam via rede Docker.

Observação:
A execução simultânea dos containers pode apresentar instabilidade devido à limitação de memória da VM (1GB).
## Endpoints (Nuvem)

API Java:
http://20.116.59.19:8080/api/transacoes

API .NET:
http://20.116.59.19:5000/api/transacoes

Obs: A aplicação foi executada em VM na Azure. Pode haver instabilidade devido à limitação de memória.
