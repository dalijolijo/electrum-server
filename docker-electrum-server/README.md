# Electrum-Server Docker Solution for Megacoin

## Permissions on Dockerhost

```sh
mkdir -p /home/electrum/mec
chmod 777 /home/electrum/mec
```

## Start/Stop
```sh
docker-compose up -d
docker-compose down
```

## Logging
```sh
docker ps
docker logs --tail 30 -f electrum-server
docker logs --tail 30 -f megacoind
```
