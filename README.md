# Docker LAMP & Elasticsearch 
Development environment for LAMP &amp; Easticsearch with Docker Compose

## setup

### Clone this repository

```
git clone https://github.com/acro5piano/docker-lamp-elasticsearch.git
cd docker-lamp-elasticsearch
docker-compose up
```

### It's done!

Go to <http://localhost:3000/> and you can see PHP works.

### Useful commands

- `docker-compose ps` shows the status of containers
- `docker exec -it <container name> bash` enter the shell of a container
- `mysql -u yourgreatapp -p yourgreatapp -D yourgreatapp -h 127.0.0.1` enter the MySQL console
- `alias dc='docker-compose'` is useful
