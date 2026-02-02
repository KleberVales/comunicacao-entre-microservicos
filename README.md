# Comunicação entre microserviços

<p align="justify">Comunicação entre microserviços é o conjunto de mecanismos e padrões usados para que diferentes microserviços de uma aplicação troquem informações e colaborem entre si. Como cada microserviço é independente e especializado em uma função (ex.: autenticação, pagamentos, pedidos), eles precisam se comunicar para que o sistema funcione de forma integrada.</p>



```css

 ├─ Síncrona
 │   ├─ REST
 │   ├─ GraphQL
 │   └─ gRPC
 │
 └─ Assíncrona
     ├─ Mensageria / Eventos
     │   ├─ RabbitMQ
     │   ├─ Kafka
     │   └─ SQS
     │
     └─ Outros
         ├─ Webhooks
         └─ Callbacks
```

## Síncrona

- [REST](https://github.com/KleberVales/comunicacao-entre-microservicos/wiki/01-REST)
- [GraphQL](https://github.com/KleberVales/comunicacao-entre-microservicos/wiki/02-GraphQL)
- [gRPC](https://github.com/KleberVales/comunicacao-entre-microservicos/wiki/03-gRPC)

## Assíncrona

- RabbitMQ
- Kafka
- SQS
