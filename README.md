1. git clone https://github.com/bastman69/docker-lumen.git folder of your choice
2. cd to the folder of your choice
2. create a .env file with the defaults
```
APP_ENV=local
APP_DEBUG=true
APP_KEY= your key here
APP_TIMEZONE=UTC

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret

CACHE_DRIVER=file
QUEUE_DRIVER=sync
```
4. install docker & docker-compose (if already installed, move on)

5. ```docker-compose up ```wait .........

6. visit ```http://localhost:8080``` in your favourite browser
