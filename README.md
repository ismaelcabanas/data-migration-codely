Execute these commands in order
* `docker compose up`, get up the postgresql and rabbitmq
* `npm run configure-rabbitmq`, configure rabbitmq
* `npm run dev`, run the application
* `npm run consume-rabbitmq`, to see how the events are consumed
* `npm run register-users`, to call creation user API each 2 seconds

To see the App and the Rabbit Admin
* http://localhost:3000/
* [Rabbit admin](http://localhost:15672/) codely/codely

In /etc/http are some requests.
