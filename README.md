# WordPress Deployment with Docker
### Windows
```
docker-compose -f ".\docker\docker-compose.yml" up
```

### Linux or Unix
```
docker-compose -f "./docker/docker-compose.yml" up
```
## Structure
- docker : docker configuration
  - db
  - php
  - phpmyadmin
  - wordpress
  - .env
  - .gitignore
  - docker-compose_M1.yml
  - docker-compose.yml
- www : project directory
  - _sql : directory sql dump
    - project_name.sql : this is sql dump file