# redash-docker-example-202111

## Setup

Run only the first time.

### Creating a volume directory

```
mkdir -p ./volumes/db/var/lib/postgresql/data
```

### Create Database

```
docker-compose run --rm server create_db
```

## Start

```
docker-compose up -d
```

# Links

* https://github.com/getredash/redash
    * https://github.com/getredash/redash/blob/master/docker-compose.yml
* https://redash.io/help/open-source/dev-guide/docker
