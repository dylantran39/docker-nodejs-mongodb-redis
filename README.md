# Docker with NodeJS-MongoDB-Redis Project

## Setup and Usage

```
# Build Docker image
$ docker build -t learning-docker:node .

# Build and run app with Docker Compose
$ docker-compose up -d

# Access app container
$ docker-compose exec app sh

# Access db container
$ docker-compose exec db sh

# Access redis container
$ docker-compose exec redis sh
```

With the server running, visit http://localhost:3000
