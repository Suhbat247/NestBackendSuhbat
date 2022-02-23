## NEST BACKEND SAMPLE PROJECT

required to install

- [Docker](https://www.docker.com/products/docker-desktop)
- [MongoDB](https://www.mongodb.com/products/compass)
- [DBeaver](https://dbeaver.io/)
- [Postman](https://www.postman.com/downloads/)

configuration

create `.env` file from `.env-sample`

installation

```
npm i
```

Run

```
npm start
npm run dev
```

Database installation in a Docker

postgresql

```cmd
docker run --name nest-postgres -e POSTGRES_PASSWORD=123 -d -p 5432:5432 postgres
```

mongodb

```cmd
docker run -d --name nest-mongo \
      -e MONGO_INITDB_ROOT_USERNAME=admin \
      -e MONGO_INITDB_ROOT_PASSWORD=password \
      mongo
```
