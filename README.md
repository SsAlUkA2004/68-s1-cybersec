# Cyber Security

## Information
- Direk Puankham (Mond)
- 6602041610071
- s6602041610071@email.kmutnb.ac.th
mond

## Environment
```sh
cp env.simple .env
```

## Runing a services
## Database
```sh
docker compose -f db.yaml up # monitoring
docker compose -f db.yaml up -d # background
```

## Admin
```sh
docker compose -f admin.yaml up # monitoring
docker compose -f admin.yaml up -d # background
```

## App
```sh
docker compose -f app.yaml up # monitoring
docker compose -f app.yaml up -d # background
```

## clear cache
```sh
docker compose -f app.yaml up --remove-orphans
```