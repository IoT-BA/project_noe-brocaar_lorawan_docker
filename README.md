Docker compose to build the entire Brocaars LoraWAN implementation (all parts of it)

Running / building the Docker images:

```bash
git clone https://github.com/hecko/brocaar-lorawan-docker.git
docker-compose up --build --force-recreate -d --remove-orphans
```

Now connect to the host, https, port 8080
