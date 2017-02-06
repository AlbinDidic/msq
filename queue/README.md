# RabbitMQ Service

## Docker Setup
docker run -d --hostname <HOST>--name switex-msq -p 15672:15672 -p 5672:5672 -e RABBITMQ_DEFAULT_USER=<USER> -e RABBITMQ_DEFAULT_PASS=<PASSWORD> rabbitmq:3-management

For more info visit the official documentation here:
https://github.com/docker-library/docs/tree/master/rabbitmq