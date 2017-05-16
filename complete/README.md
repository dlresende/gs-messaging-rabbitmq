Build and test:
`mvn clean verify`

Run locally:
`mvn spring-boot:run`

Deploy to CF:
`cf push`

Reconfigure CF health check:
`cf set-health-check gs-messaging-rabbitmq process`
