# Electrum-Server Docker Solution for Bitcore

## Permissions on Dockerhost

```sh
mkdir -p /home/electrum/btx
chmod 777 /home/electrum/btx
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
docker logs --tail 30 -f bitcored
```
