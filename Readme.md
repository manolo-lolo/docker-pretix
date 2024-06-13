# Pretix docker-compose template

## Setup
```
git clone <this repository>
mkdir ./volumes/{data,db}
chown 15371:15371 volumes/data/
cp env.example .env
```
Fill in the gaps in `pretix.cfg` and `.env`.


## Basic and other helpful commands
Start pretix:

```bash
sudo docker-compose up -d
```

Stop pretix:
```bash
sudo docker-compose down
```

Look (and keep looking) at pretix logs:
```bash
sudo docker logs -f pretix_app
```


