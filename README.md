# docker-ragemp-mysql

Simple Docker container for RAGE Multiplayer and MySQL.


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file:

- `MYSQL_VERSION`
- `MYSQL_USER`
- `MYSQL_PASSWORD`
- `MYSQL_DATABASE`
- `RAGEMP_CLIENT`
- `RAGEMP_SERVER`
- `RAGEMP_MODULES`

See: [.env.example](.env.example)
## Usage

Build containers:

```bash
docker-compose up -d --no-start
```

Start containers:

```bash
docker-compose start
```

Stop containers:

```bash
docker-compose stop
```

Remove containers:

```bash
docker-compose down
```
