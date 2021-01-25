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

## Format commit message

```
type(scope?): subject
-> type can be one of the below values
build: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
ci: Changes to our CI configuration files and scripts (example scopes: Gitlab CI, Circle, BrowserStack, SauceLabs)
chore: add something without touching production code (Eg: update npm dependencies)
docs: Documentation only changes
feat: A new feature
fix: A bug fix
perf: A code change that improves performance
refactor: A code change that neither fixes a bug nor adds a feature
revert: Reverts a previous commit
style: Changes that do not affect the meaning of the code (Eg: adding white-space, formatting, missing semi-colons, etc)
test: Adding missing tests or correcting existing tests
```

With the server running, visit http://localhost:3000
