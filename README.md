# Elasticsearch Docker Composition

This repository includes a raw Elasticsearch Kibana composition.

## Setup
1. create `.env` files and use your preferred credentials
```
cp ./kibana/.env.example ./kibana/.env
cp ./elasticsearch/.env.example ./elasticsearch/.env
```

**Please note** The username should be `elastic` for some reasons.
If not you'll get an error.

2. start composition
```
docker-compose up -d
```
