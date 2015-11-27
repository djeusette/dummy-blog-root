### dummy-blog-root

This is a simple repository that contains the services composing the dummy blog app.

#### dotenv files

##### dummy-blog/.env

```
DATABASE_HOST=postgres
DATABASE_NAME=dummy-blog
DATABASE_USERNAME=xxx
DATABASE_PASSWORD=xxx
WORDS_GENERATOR_URL=...
```

##### .env.postgres

```
POSTGRES_USER=dummy-blog
POSTGRES_PASSWORD=dummy-pwd
```

#### Run

```
docker-compose run dummy-blog rake db:setup
```

```
docker-compose up
```
