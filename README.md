# CockroachDB Tests
Spin up the 3 node CockroachDB cluster with docker compose:
```bash
$ docker-compose up -d
```

Then the tests can be run from the individual folders:
```bash
$ cd basic-sample && go run main.go
```