Docker-gerrit
---

Lauch [Gerrit](https://www.gerritcodereview.com/) via docker-compose.

# Usage

```shell
# Start database first
docker-compose up -d db
# Then start gerrit
docker-compose up -d gerrit
```

# References
* [Postgres Docker image](https://hub.docker.com/_/postgres/)
* [openfrontier/docker-gerrit Docker image](https://github.com/openfrontier/docker-gerrit)
