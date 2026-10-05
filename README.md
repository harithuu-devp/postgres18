# PostgreSQL 18 Container for Local Development

## 1. Clone repo
```
git clone https://github.com/harithuu-devp/postgres18.git
```

If use docker, rename compose.yml to docker-compose.yml

## 2. inside postgres18, run compose up

````
cd postgres18
podman-compose up -d

<!-- if use docker -->
docker-compose up -d
````
## 3. Install pgAdmin4 to easily manage database. 