## Cyber Security

## Owner

* 6702041511047
* Prakaidao Phonson
* s6702041511047@email.kmutnb.ac.th

## Environment
```sh
cp env.simple .env
```

## Runnig services
### Database

```sh
# run database only
docker compose -f db.yaml up

# run database in background
docker compose -f db.yaml up -d

```

### Application

```sh
# run application service
docker compose -f app.yaml up

# run application in background
docker compose -f app.yaml up -d
```

### pgAdmin

```sh
# run pgAdmin service
docker compose -f admin.yaml up

# run pgAdmin in background
docker compose -f admin.yaml up -d
```