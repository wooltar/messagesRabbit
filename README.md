![alt text](https://www.rabbitmq.com/img/RabbitMQ-logo.svg)
![alt text](https://hapijs.com/public/img/logo.svg)

# Hapi server with RabbitMQ (dockerized)
ARQ example with hapi server and RabbitMQ

## Deploy environment
sudo docker-compose up

In error case :
gpg: keyserver receive failed: Cannot assign requested address

retry
sudo docker-compose up

## Send message

**POST** http://localhost:8000/message

```json
    "body": {
        "message": "hello kike"
    }
 ```

